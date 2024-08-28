<script setup>
import debounce from 'lodash.debounce';

const socket = ref()
const coins = ref([])
const visibleCoins = ref([]);
const coinsRef = ref(null);
const listCoinsRefs = ref([]);

const update_coin = (name, value) => {
    coins.value = coins.value.map(el => el.symbol === name ? {
        symbol: name,
        last: value.last,
        open_24h: value.open24h,
        vol_24h: value.vol24h
    } : el)
}

let observer;

const debouncedWebsocket = debounce(() => {
    if (socket.value) {
        socket.value.close()
    }

    socket.value = new WebSocket('wss://wsg.ok-ex.io/ws');

    socket.value.onopen = () => {
        const args = visibleCoins.value.map(coin => { return { channel: "tickers", instId: coin.symbol } })
        socket.value.send(JSON.stringify({
            op: "subscribe",
            args: args
        }));
    };

    socket.value.addEventListener('message', (event) => {
        const { data: data } = JSON.parse(event.data)
        data.forEach(element => {
            update_coin(element.instId, element)
        });
    })
}, 500);

const updateVisibleItems = (entries) => {
    entries.forEach(entry => {
        const index = listCoinsRefs.value.indexOf(entry.target);

        if (entry.isIntersecting) {
            if (!visibleCoins.value.includes(coins.value[index])) {
                visibleCoins.value.push(coins.value[index]);
            }
        } else {
            visibleCoins.value = visibleCoins.value.filter(item => item.symbol !== coins.value[index].symbol);
        }
        debouncedWebsocket()
    });
};

onMounted(async () => {
    await $fetch('market/tickers', {
        baseURL: 'https://api.ok-ex.io/oapi/v1',
        onResponse({ request, response, options }) {
            response._data = response._data.tickers.sort((a, b) => b.vol_24h_pair - a.vol_24h_pair)
            coins.value = response._data
        },
    })

    // await nextTick();

    observer = new IntersectionObserver(updateVisibleItems, {
        root: coinsRef.value,
        rootMargin: '-128px 0px 0px 0px',
        threshold: 0.1
    });

    listCoinsRefs.value.forEach(item => {
        observer.observe(item);
    });
})

onBeforeUnmount(() => {
    if (socket.value) {
        socket.value.close()
    }
    if (observer) {
        observer.disconnect();
    }
})

</script>

<template>
    <div class="h-full">
        <ul class="flex flex-col relative gap-4 p-4" dir="ltr" :ref="coinsRef">
            <li class="py-3 flex justify-between text-gray-400 sticky top-24 bg-white">
                <div>جفت</div>
                <div>تغییر ۲۴ ساعته</div>
                <div>قیمت</div>
            </li>
            <li class="p-2 grid grid-cols-3 items-center cursor-pointer hover:bg-neutral-50 rounded-xl gap-2"
                v-for="(coin, index) in coins" :key="coin.symbol" :ref="el => listCoinsRefs[index] = el">
                <div class="flex items-center gap-3"><img
                        :src="`https://dl.ok-ex.io/coins/128/color/${coin.symbol.split('-')[0].toLowerCase()}.png`"
                        :alt="coin.symbol" class="w-6 h-6 rounded-full">
                    <span class="text-gray-700">{{ coin.symbol.split('-')[0] }}</span>
                </div>
                <div class="text-center rounded-xl py-3 font-semibold w-24 mx-auto"
                    :class="parseFloat(coin.open_24h) <= parseFloat(coin.last) ? 'text-green-500 bg-green-50' : 'text-red-500 bg-red-50'">
                    <span>{{
                        ((parseFloat(coin.last) - parseFloat(coin.open_24h)) /
                            parseFloat(coin.open_24h) * 100).toFixed(2)
                    }}%</span>
                </div>
                <div class="text-end font-semibold"><span class="text-gray-700">{{ coin.last }} {{
                    coin.symbol.split('-')[1] }}</span></div>
            </li>
        </ul>
    </div>
</template>
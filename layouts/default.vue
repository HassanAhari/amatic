<script setup>
const route = useRoute()

const menus = [
    { title: 'صفحه اصلی', name: 'index', to: '/' },
    { title: 'سوالات متداول', name: 'faq', to: '/faq' },
]

</script>

<template>
    <div class="min-h-screen flex flex-col">
        <AppHeader></AppHeader>
        <div class="flex flex-row">
            <aside class="w-64 p-6 h-full sticky top-24">
                <ul>
                    <li v-for="menu in menus" :key="menu.name" class="p-2 my-2">
                        <NuxtLink :to="menu.to" :class="route.name === menu.name && 'text-primary'">{{ menu.title }}
                        </NuxtLink>
                    </li>
                </ul>
            </aside>
            <main class="flex-1 p-6 relative">
                <slot></slot>
            </main>
            <!-- <div class="mx-auto max-w-screen-xl px-4 py-8 sm:px-6 sm:py-8 lg:px-8 overflow-y-auto">
                <div class="flex flex-col items-start gap-4 md:flex-row md:justify-between overflow-y-auto">
                    <aside class="w-1/3">aside</aside>
                    
                </div>
            </div> -->
        </div>
    </div>
</template>
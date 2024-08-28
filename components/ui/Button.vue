<script setup lang="ts">
defineProps<{
    text?: string
    class?: string
}>()
</script>

<template>
    <button
        class="inline-flex items-center justify-center gap-1.5 rounded border border-gray-200 bg-white px-5 py-3 text-gray-900 transition hover:text-gray-700"
        :class="class">
        <slot></slot>
    </button>
</template>
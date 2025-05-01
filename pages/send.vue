<script setup lang="ts">
useHead({
    title: `Send — My Awesome Nexa Wallet`,
    meta: [
        { name: 'description', content: `Nexa Studio makes building your next BIG idea effortless.` }
    ],
})
</script>

<template>
    <Send :isFullScreen="true" />
</template>

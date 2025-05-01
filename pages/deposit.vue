<script setup lang="ts">
useHead({
    title: `Deposit — My Awesome Nexa Wallet`,
    meta: [
        { name: 'description', content: `Nexa Studio makes building your next BIG idea effortless.` }
    ],
})
</script>

<template>
    <Deposit :isFullScreen="true" />
</template>

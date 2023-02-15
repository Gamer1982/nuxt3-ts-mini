<template>
    <div class="flex grow">
        <button @click="count++">increment</button>
        <p>{{ count }}</p>
        <button @click="count--">decrement</button>
    </div>
</template>

<script setup lang="ts">
const count = ref<number>(0)

</script>

<style scoped>

</style>
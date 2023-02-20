<template>
    <div>
        <h2>This is xiaomi {{ $route.params.model }}</h2>
        <p>new version - {{ newModel }}</p>
        <p>{{ $options }}</p>
    </div>
</template>

<script setup >
const newModel = computed(() => {
    return useRoute().params
})

useHead({
    title: `nuxt3`
})

</script>

<style scoped>

</style>
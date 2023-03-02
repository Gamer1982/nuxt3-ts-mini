<template>
    <div>
        <p>new version - {{ newModel.model }}</p>

        <nuxt-link to="/xiaomi/xiaomi-mi-11" class="shadow-lg text-center">
            <h2>This is {{ $route.params.model }}</h2>
            <img :src="`/img/${$route.params.model}` + '.png'" alt="">
        </nuxt-link>
    </div>
    <h2>{{ str }}</h2>
</template>

<script setup >
const newModel = computed(() => {
    return useRoute().params
})

useHead({
    title: `nuxt3`
})




console.log(str);

</script>

<style scoped></style>
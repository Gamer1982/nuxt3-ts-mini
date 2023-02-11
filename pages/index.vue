<template>
 <NuxtLink to="/">Home</NuxtLink>
 <p>--------------------------------</p>
<NuxtLink to="about">About</NuxtLink>
<p>----------------------------------</p>

<button @click="goTooAbout">Go too About</button>

 Hello World
</template>

<script setup lang="ts">
function goTooAbout(){
    navigateTo('about')
}

</script>

<style scoped>

</style>
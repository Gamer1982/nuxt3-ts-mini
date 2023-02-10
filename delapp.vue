<template>
  <button @click="changeTogle">Togle</button>
  <!-- <Nuxt2023Count /> -->
  <component :is="MyComponent" />

  <NuxtPage />
</template>

<script setup lang="ts">

const MyComponent = shallowRef(resolveComponent('Nuxt2023Count'))

const changeTogle = () => {
  MyComponent.value === resolveComponent('Nuxt2023Count') ? MyComponent.value = resolveComponent('HomeWelcome') : MyComponent.value = resolveComponent('Nuxt2023Count')
}


</script>
 
<style scoped>

</style>

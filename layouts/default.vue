<template>
    <div class="text-lg container flex flex-col p-3 m-3 justify-between bg-slate-400">
        <header class="bg-green-500 flex text-orange-200 ">
            <h2>Header</h2>
        </header>
        <main class="flex bg-purple-700 text-white flex-col justify-around grow">
            <slot />
        </main>
        <footer class="flex bg-emerald-900 text-cyan-300  ">
            <h2>footer</h2>
            <NuxtLink to="/">Home</NuxtLink>
            <p>--------------------------------</p>
            <NuxtLink to="about">About</NuxtLink>
            <p>----------------------------------</p>
        </footer>
    </div>
</template>

<script setup lang="ts">


</script>

<style scoped>

</style>
<template>
    <div class="text-lg container flex flex-col p-3 m-3 justify-between bg-slate-400">
        <header class="bg-green-500 flex text-orange-200 ">
            <h2>Header</h2>
        </header>
        <main class="flex bg-purple-700 text-white flex-col justify-around grow">
            <slot />
        </main>
        <footer class="flex justify-between bg-emerald-900 text-cyan-300 shadow">
            <NuxtLink to="/">Home</NuxtLink>
            <NuxtLink to="/about">About</NuxtLink>
            <NuxtLink to="/xiaomi">Xiaomi</NuxtLink>
        </footer>
    </div>
</template>

<script setup lang="ts">


</script>

<style scoped>

</style>
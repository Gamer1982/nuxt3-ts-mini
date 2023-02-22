<template>
    <div class="text-lg p-4 m-4  flex flex-col justify-between bg-slate-400">
        <header class="bg-green-500 flex text-orange-200 p-2">
            <h2>Header</h2>
        </header>
        <main class="flex bg-purple-700 text-white flex-col justify-around grow p-2 mt-1 mb-1">
            <slot />
        </main>
        <footer class="flex justify-between bg-emerald-900 text-cyan-300 shadow p-2">
            <NuxtLink to="/">Home</NuxtLink>
            <NuxtLink to="/about">About</NuxtLink>
            <NuxtLink to="/xiaomi">Xiaomi</NuxtLink>
        </footer>
    </div>
</template>

<script setup lang="ts">


</script>

<style scoped></style>
<template>
    <div>
        <header>
            <h2>Header</h2>
        </header>
        <main class="flex ">
            <slot />
        </main>
        <footer>
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
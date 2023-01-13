<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <div>
        <a target="_blank" href="https://vitejs.dev">
            <img alt="Vite logo" src="/vite.svg" class="logo" />
        </a>
        <img
            :key="i"
            v-for="i in items"
            alt="Vue logo"
            src="./assets/logo.png"
        />
        <a href="https://vuejs.org/" target="_blank">
            <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
        </a>
    </div>
    <HelloWorld msg="Vite + Vue" />
</template>

<script>
var test = 'test'
</script>

<style scoped>
.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
}
.logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #d3c1af; background-color: #2c3e50;
  margin-top: 60px; width: 100%; min-height: 100%;
}
button {
    background: none;
    border: solid 2px;
    border-radius: 2em;
    padding: 0.75em 2em;
    color: #44bb84
}
a {
  color: #44bb84; text-decoration: none;
} :global(body){ background-color: #2c3e50}
</style>

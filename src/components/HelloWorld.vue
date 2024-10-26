<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>Archsenal</h1>

  <p>
    A website to mirror and host some of my projects.
  </p>
  
  <p>
    <a href="https://emulator.archiiv.cc/" target="_blank">
      Placeholder
    </a>
    |
    <a href="https://music.archiiv.cc/" target="_blank">Placeholder</a>
  </p>

  <button type="button" @click="count++">count is: {{ count }}</button>
</template>
<style> template { background-color: #2c3e50; }</style>
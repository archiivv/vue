<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>Arch-Opensky</h1>

  <p>
    My Personal Links:
    <a href="https://archiiv.cc/" target="_blank">Main Website</a>
    +
    <a href="https://github.com/archiivv/" target="_blank">Github</a>
  </p>
  <p>Projects</p>
  <p>
    <a href="https://emulator.archiiv.cc/" target="_blank">
      Emulator
    </a>
    |
    <a href="https://music.archiiv.cc/" target="_blank">Mini Music Player</a>
  </p>

  <button type="button" @click="count++">count is: {{ count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

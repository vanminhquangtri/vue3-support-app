<script setup lang="ts">
import { onMounted } from 'vue'

onMounted(() => {
  setTimeout(() => {
    window.location.reload()
  }, 800000)
})
</script>

<template>
  <iframe
    src="https://nvmportfolio.netlify.app/blogs"
    frameborder="0"
    style="width: 100vw; height: 100vh; max-width: 100%; margin: auto"
  ></iframe>
</template>

<style scoped></style>

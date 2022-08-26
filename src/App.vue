<script setup>
  import { ref } from 'vue'
  const title = ref('Hello There ✋')
</script>

<template>
  <main class="flex justify-center min-h-screen items-center">
    <h1 class="text-6xl font-thin text-slate-800">{{ title }}</h1>
  </main>
</template>

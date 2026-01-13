<script setup>
import NavMenu from '@/components/NavMenu.vue'
</script>

<template>
  <div class="flex h-full flex-col">
    <NavMenu />
    <RouterView />
  </div>
</template>

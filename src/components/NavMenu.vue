<script setup>
const linkClass =
  'hover:underline hover:underline-offset-4 [&.router-link-active]:underline [&.router-link-active]:underline-offset-4'
</script>

<template>
  <nav class="flex justify-center gap-4">
    <RouterLink
      to="/"
      :class="linkClass"
    >
      Home
    </RouterLink>
    <RouterLink
      to="/other"
      :class="linkClass"
    >
      Other
    </RouterLink>
  </nav>
</template>

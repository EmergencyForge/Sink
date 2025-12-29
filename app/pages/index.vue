<script setup lang="ts">
await navigateTo('https://emergencyforge.de', { external: true })
</script>

<template>
  <main class="flex flex-col justify-center">
    <HomeTwitter />
    <HomeHero />
    <HomeFeatures />
    <HomeLogos />
    <HomeCta />
  </main>
</template>

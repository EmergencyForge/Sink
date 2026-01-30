<script setup lang="ts">
await navigateTo('https://emergencyforge.de', { external: true })
</script>

<template>
  <div class="flex flex-col justify-center">
    <HomeHero />
    <HomeLogos />
    <HomeFeatures />
    <HomeStats />
    <HomeTestimonials />
    <HomeCta />
  </div>
</template>

<script setup lang="ts">
</script>

<template>
  <!-- Edit this file to play around with Nuxt but never commit changes! -->
  <div>
    <NuxtLink to="/page1">Page 1</NuxtLink>
    <NuxtLink to="/page2">Page 2</NuxtLink>
    <NuxtLink to="/page3">Page 3</NuxtLink>
    <NuxtLink to="/page4">Page 4</NuxtLink>
    <NuxtLink to="/page5">Page 5</NuxtLink>
    <NuxtLink to="/page6">Page 6</NuxtLink>
    <NuxtLink to="/product/1">Product 1</NuxtLink>
    <NuxtLink to="/product/2">Product 2</NuxtLink>
    <NuxtLink to="/product/3">Product 3</NuxtLink>
    <div>
      <NuxtPage :keepalive="{max: 2, exclude: ['/page6']}" />
    </div>
  </div>
</template>

<style scoped>

</style>

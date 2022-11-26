<script setup lang="ts">
const route = useRoute();

onMounted(() => {
  console.log(`${route.path} mounted`);
})
onUnmounted(() => {
  console.log(`${route.path} unmounted`);
})
onActivated(() => {
  console.log(`${route.path} activated`);
})
onDeactivated(() => {
  console.log(`${route.path} deactivated`);
})
</script>

<template>
  <div>
    Page 1
  </div>
</template>

<style lang="less">
</style>

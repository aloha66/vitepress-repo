<template>
  <h1>Customee Layout!</h1>
  <Content /><!-- make sure to include markdown outlet -->
</template>
<script setup lang="ts">
import { onMounted } from "vue-demi"; // in vite,cli is ok ,not work in vitepress
// import { onMounted } from "vue"; // ok

onMounted(() => {
  console.log("onMounted");
});
</script>

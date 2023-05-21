<template>
  <div class="app">
    <NavMenu />
    <router-view />
  </div>
</template>
<script setup>
import NavMenu from "@/components/NavMenu.vue";
</script>

<style scoped>
.app {
  display: flex;
  height: 100vh;
  background: linear-gradient(252.9deg, #700b11 1.09%, #3c0f17 98.4%);
}
</style>

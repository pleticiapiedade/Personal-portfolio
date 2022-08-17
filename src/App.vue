<script setup>
import { RouterLink, RouterView } from "vue-router";
import HeaderContent from "./components/HeaderContent.vue";
</script>
<template>
  <header class="align">
    <HeaderContent />
  </header>

  <RouterView />
</template>

<style scoped lang="scss">

header {
  width: 100%;
  height: 7rem;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 10;

  display: flex;
  align-items: center;

  svg {
    max-width: 30px;
  }
}
</style>

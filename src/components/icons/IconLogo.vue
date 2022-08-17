<script setup>
import IconCode from "./IconCode.vue";
</script>

<template>
  <div class="brand">
    <IconCode />
    <div class="brand-text">
      <div class="brand-name">Letícia</div>
      <div class="brand-last">Front-end Developer</div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.brand {
  width: 18rem;
  color: #fff;
  display: flex;
  gap: 1rem;

  svg{
    width:2.5rem;
  }

  .brand-name {
    font-weight: 600;
    font-size: 1.7rem;
  }
  .brand-last {
    font-weight: 500;
    font-size: .9rem;
    margin-top: -.7rem;
  }
}
</style>

<script setup>
import Logo from "./icons/IconLogo.vue";

import IconLinkedin from "./icons/IconLinkedin.vue";
import IconInstagram from "./icons/IconInstagram.vue";
import IconGithub from "./icons/IconGithub.vue";
import IconGitlab from "./icons/IconGitlab.vue";
</script>

<template>
  <div class="wrapper">
    <a href="#">
      <div class="logo">
        <Logo />
      </div>
    </a>
    <div class="social-icons">
      <a href="#"><IconLinkedin /></a>
      <a href="#"><IconInstagram /></a>
      <a href="#"><IconGithub /></a>
      <a href="#"><IconGitlab /></a>
    </div>
  </div>
</template>

<style scoped lang="scss">
@import "../sass/variables.scss";

svg {
  max-width: 20px;
}

.wrapper {
  display: flex;

  .social-icons,
  .social-icons > a {
    display: flex;
    align-items: center;
  }
  .social-icons {
    gap: 1rem;
    a {
      &:hover {
        svg {
          fill: $blue;
        }
      }
    }
  }
}
</style>

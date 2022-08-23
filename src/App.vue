<template>
  <div>
    <BaseJumbo> </BaseJumbo>
    <BaseHeader class="container-xxxl" :logo="logo" :menu="menu"></BaseHeader>
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";
import BaseJumbo from "./components/BaseJumbo.vue";
export default {
  name: "App",
  components: { BaseHeader, BaseJumbo },
  data() {
    return {
      logo: "logotype.png",
      menu: ["Home", "About", "Projects", "Services", "Blog", "Contact"],
    };
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss";
@import "~bootstrap/scss/bootstrap";
</style>

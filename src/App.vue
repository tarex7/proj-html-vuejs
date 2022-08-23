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
@import "~bootstrap/scss/bootstrap";
@import "./assets/scss/style.scss";
@import url("https://fonts.googleapis.com/css2?family=Bai+Jamjuree:wght@200;300;400;500;600;700&display=swap");
body {
  font-family: "Bai Jamjuree", sans-serif;
}
</style>

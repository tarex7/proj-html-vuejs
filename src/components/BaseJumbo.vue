.
<template>
  <div class="jumbotron d-flex justify-content-end">
    <img
      class="img-fluid"
      src="../assets/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg"
      alt="young-architect-woman-on-meeting"
    />
  </div>
</template>

<script>
export default {
  name: "BaseJumbo",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";
.jumbotron {
  background-color: $primary-color;
  height: 996px;
  img {
    height: 100%;
  }
}
</style>

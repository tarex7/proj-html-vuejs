.
<template>
  <div class="jumbotron">
    <img
      class="img-fluid float-end"
      src="../assets/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg"
      alt="young-architect-woman-on-meeting"
    />
    <div class="content">
      <div class="d-flex align-items-center">
        <div class="line me-4"></div>
        <h5 class="text-white text-uppercase">
          Always the best way you need it
        </h5>
      </div>
      <h1 class="text-white mb-5">The best business consulting</h1>
      <a href="#" class="btn btn-primary rounded-0 ms-2">Read more</a>
      <a href="#"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          width="12"
          height="12"
          fill="#39ffbf"
          class="bi bi-play-fill ms-5"
          viewBox="0 0 16 16"
        >
          <path
            d="m12.899 8.697-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 0 1 0 1.393z"
          /></svg
      ></a>
    </div>
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
  height: 996px;
  overflow: hidden;
  .content {
    position: absolute;
    top: 30%;
    left: 8%;
    width: 40%;
    .bi-play-fill {
      border: 2px solid #fff;
      border-radius: 50%;
      width: 55px;
      height: 55px;
      padding: 12px;
      &:hover {
        fill: $third-color;
      }
    }
  }

  h1 {
    font-size: 6.5rem;
    text-transform: uppercase;
    font-weight: bold;
    line-height: 100px;
  }

  h5 {
    letter-spacing: 1.8px;
    opacity: 0.8;
  }
  img {
    height: 1150px;
  }

  .line {
    height: 3px;
    width: 7%;
    background-color: $secondary-color;
  }
}
</style>

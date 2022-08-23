<template>
  <div>
    <BaseJumbo> </BaseJumbo>
    <BaseHeader class="container-xxxl" :logo="logo" :menu="menu"></BaseHeader>
    <section id="consultants" class="bg-white row">
      <div class="offset-2 col">
        <div class="d-flex align-items-center my-5">
          <h3 class="text-uppercase mx-4 fw-bold flex-shrink-0">
            Our consultants can help you
          </h3>
          <div class="line-wide"></div>
        </div>
        <div class="row">
          <div
            class="col d-flex flex-column align-items-center justify-content-start"
          >
            <div class="d-flex align-items-start">
              <img class="me-5" src="./assets/icon-1.png" alt="" />
              <div class="pe-5">
                <h4 class="text-uppercase fw-bold">Statistical consulting</h4>
                <p>
                  When, while lovely valley teems with vapour around meand
                  eridian sun strikes the upper impenetrable foliage of my
                  trees, and but a
                </p>
              </div>
            </div>
            <div class="pe-5">
              <h4 class="text-uppercase fw-bold">Statistical consulting</h4>
              <p>
                When, while lovely valley teems with vapour around meand eridian
                sun strikes the upper impenetrable foliage of my trees, and but
                a
              </p>
            </div>
          </div>
          <div
            class="col d-flex flex-column align-items-center justify-content-center"
          >
            <div class="p-5">
              <h4 class="text-uppercase fw-bold">Statistical consulting</h4>
              <p>
                When, while lovely valley teems with vapour around meand eridian
                sun strikes the upper impenetrable foliage of my trees, and but
                a
              </p>
            </div>
            <div class="p-5">
              <h4 class="text-uppercase fw-bold">Statistical consulting</h4>
              <p>
                When, while lovely valley teems with vapour around meand eridian
                sun strikes the upper impenetrable foliage of my trees, and but
                a
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
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
</style>

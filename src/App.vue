<template>
  <div>
    <BaseJumbo> </BaseJumbo>
    <BaseHeader class="container-xxxl" :logo="logo" :menu="menu"></BaseHeader>
    <section id="consultants" class="bg-white">
      <div class="h-100">
        <div class="offset-2 d-flex align-items-center my-5">
          <h3 class="text-uppercase mx-4 fw-bold flex-shrink-0">
            Our consultants can help you
          </h3>
          <div class="line-wide"></div>
        </div>
        <!--  -->
        <div class="d-flex offset-2">
          <div class="col my-5">
            <div class="d-flex align-items-start ms-4">
              <img class="me-5" src="./assets/icon-1.png" alt="" />
              <div class="pe-5 mt-1">
                <h4 class="text-uppercase fw-bold">Statistical consulting</h4>
                <p>
                  When, while lovely valley teems with vapour around meand
                  eridian sun strikes the upper impenetrable foliage of my
                  trees, and but a
                </p>
              </div>
            </div>
          </div>
          <div class="col my-5">
            <div class="d-flex align-items-start">
              <img class="me-5" src="./assets/icon-1.png" alt="" />
              <div class="pe-5 mt-1">
                <h4 class="text-uppercase fw-bold">Digital consulting</h4>
                <p>
                  When, while lovely valley teems with vapour around meand
                  eridian sun strikes the upper impenetrable foliage of my
                  trees, and but a
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="d-flex offset-2">
          <div class="col my-5">
            <div class="d-flex align-items-start ms-4">
              <img class="me-5" src="./assets/icon-1.png" alt="" />
              <div class="pe-5 mt-1">
                <h4 class="text-uppercase fw-bold">Banking consulting</h4>
                <p>
                  When, while lovely valley teems with vapour around meand
                  eridian sun strikes the upper impenetrable foliage of my
                  trees, and but a
                </p>
              </div>
            </div>
          </div>
          <div class="col my-5">
            <div class="d-flex align-items-start">
              <img class="me-5" src="./assets/icon-1.png" alt="" />
              <div class="pe-5 mt-1">
                <h4 class="text-uppercase fw-bold">Enterprise consulting</h4>
                <p>
                  When, while lovely valley teems with vapour around meand
                  eridian sun strikes the upper impenetrable foliage of my
                  trees, and but a
                </p>
              </div>
            </div>
          </div>
        </div>
        <!--  -->
      </div>
    </section>
    <section id="about">
      <div class="d-flex">
        <img
          src="./assets/business-people-working-together-on-project-and-5FHSKBL.jpg"
          alt=""
        />
        <div class="text-white d-flex align-items-center ms-5">
          <div class="content-text ps-5">
            <div class="d-flex align-items-end mb-4">
              <div class="line me-4 mb-1"></div>
              <h5 class="text-uppercase m-0">About us</h5>
            </div>
            <h2 class="text-uppercase fw-bold w-75">
              We make your strategy work
            </h2>
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
              thousand unkwown plants are noticed when I hear the buzz of the
              little world among the stalks, and grow familiar indescribable
              forms of the insects and flies, then I feel the presence of the
              Almighty.
            </p>
          </div>
        </div>
      </div>
      <div class="banner d-flex py-5">
        <div class="col d-flex align-items-center my-5">
          <h3 class="offset-4 text-uppercase fw-bold ps-5 text">
            We help to deliver the business case
          </h3>
        </div>
        <div class="col d-flex align-items-center">
          <p class="w-50 ms-5">
            When, while lovely valley teems with vapour around meand eridian sun
            strikes the upper impenetrable foliage of my trees, and but a
            thousand unkwown
          </p>
        </div>
        <a href="#" class="btn btn-secondary">get started</a>
      </div>
      <div class="offset-1"></div>
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

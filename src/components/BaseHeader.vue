.
<template>
  <div>
    <header class="container-xxxl">
      <nav class="d-flex align-items-center justify-content-between">
        <a href="#">
          <img
            :src="require(`../assets/${logo}`)"
            alt="logo"
            id="logo"
            class="img-fluid"
          />
        </a>
        <ul class="menu d-flex">
          <li
            class="d-flex align-items-start mt-2"
            v-for="(item, i) in menu"
            :key="item[i]"
          >
            <a class="hover" href="#">{{ item }}</a>
          </li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
export default { name: "BaseHeader", props: { logo: String, menu: Array } };
</script>

<style lang="scss" scoped>
header {
  position: fixed;
  z-index: 5;
  top: 0;
  right: 0;
  left: 0;
}
nav {
  height: 70px;
  line-height: 60px;
  #logo {
    width: 120px;
  }
  li {
    list-style: none;
  }

  a.hover {
    text-decoration: none;
    text-transform: uppercase;
    margin: 0 15px;
    border-top: 6px transparent solid;
    color: #fff;
    transition: all 0.3s;
    opacity: 0.7;
    &:hover {
      border-top: 6px #fff solid;
      opacity: 1;
    }
  }
}
</style>

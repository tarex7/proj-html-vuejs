.
<template>
  <div>
    <header class="container-xxxl">
      <nav class="d-flex align-items-center justify-content-between">
        <img
          :src="require(`../assets/${logo}`)"
          alt="logo"
          id="logo"
          class="img-fluid"
        />
        <ul class="menu d-flex">
          <li
            class="d-flex align-items-start mt-3"
            v-for="(item, i) in menu"
            :key="item[i]"
          >
            <a href="#">{{ item }}</a>
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
  line-height: 70px;
  #logo {
    width: 120px;
  }
  li {
    list-style: none;
  }

  a {
    text-decoration: none;
    text-transform: uppercase;
    margin: 0 10px;
    border-top: 7px transparent solid;
    color: #fff;
    &:hover {
      border-top: 7px #fff solid;
    }
  }
}
</style>

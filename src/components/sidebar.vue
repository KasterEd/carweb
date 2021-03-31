<template>
  <div class="sidebar">
    <div class="user">
      <a href="#"><i class="gg-user"></i></a>
    </div>
    <div class="favorate">
      <a href="#"><i class="gg-eye"></i></a>
    </div>
    <div class="shopping-cart">
      <a href=""><i class="gg-shopping-cart"></i></a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.sidebar {
  position: fixed;
  top: 0;
  right: 0px;
  height: 100vh;
  width: 1.5vw;
  background: #ccc;
  display: flexbox;
  justify-content: flex-end;
}
.favorate img {
  width: 30px;
  height: 30px;
}
a,
a:hover,
a:focus,
a:active {
  text-decoration: none;
  color: inherit;
}
@import url("https://css.gg/eye.css");
</style>
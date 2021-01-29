<template>
  <div class="navbar">
    <ul class="navbar_list">
      <li class="navbar_item">
        <a href="#">Home</a>
      </li>
      <li class="navbar_item">
        <a href="#" v-scroll-to="'#about'">About</a>
      </li>
      <li class="navbar_item">
        <a href="#">Resume</a>
      </li>
      <li class="navbar_item">
        <a href="#">Works</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  &_list {
    display: flex;
  }
  &_list li:not(:last-child) {
    margin-right: 10px;
  }
  &_item a {
    font-size: 18px;
    color: #ffffff;
    text-transform: uppercase;
  }
  &_item a:hover {
    color: #3fb984;
    text-decoration: none;
    transition: 0.5s;
  }
}
</style>

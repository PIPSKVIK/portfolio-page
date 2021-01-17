<template>
  <header class="home">
    <div class="container">
      <Navbar />
      <div class="home_title-wrapper">
        <h1 class="home_title">i'm Milovanov Alexander</h1>
      </div>
    </div>
  </header>
</template>

<script>
import Navbar from "@/components/Navbar";
export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>

<style lang="scss" scoped>
.home {
  height: 100vh;
  width: 100%;
  background-image: url("../../assets/backgroundImage/homePageBackground.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  text-align: center;
  overflow: hidden;

  &_title-wrapper {
  }

  &_title {
    color: #ffffff;
    font-size: 50px;
  }
  .container {
    width: 85%;
    margin: 40px auto;

    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>

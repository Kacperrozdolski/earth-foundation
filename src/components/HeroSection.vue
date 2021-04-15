<template>
  <section>
    <nav>
      <div class="left">
        <span>Home</span><span>About</span><span>Projects</span
        ><span>Partners</span>
      </div>
      <div class="center">
        <span>Earth Foundation</span>
        <img src="../assets/logo.svg" />
      </div>
      <div class="right">
        <span>Mission</span><span>News</span><span>FAQ</span><span>Share</span>
      </div>
    </nav>
    <main></main>
  </section>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style lang="scss" scoped>
section {
  min-height: 100vh;
  width: 100%;
  background-image: url("../assets/heroImage.png");
  background-position: center;
  background-size: cover;
  display: flex;
  flex-direction: column;
  align-items: center;
  nav {
    height: 10vh;
    width: 90%;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    color: white;
    .left {
      width: 30%;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .center {
      min-width: 20%;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      span {
        font-size: 2.5rem;
      }
      img {
        height: 100%;
      }
    }
    .right {
      width: 30%;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
  }
  main {
    height: 90vh;
    width: 90%;
  }
}
</style>

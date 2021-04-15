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
        <span>Mission</span><span>News</span><span>FAQ</span
        ><span
          >Share
          <img src="../assets/smallLogo.svg" />
        </span>
      </div>
    </nav>
    <main>
      <div class="hero-content">
        <h1>Transforming Cebuano lives by restoring the environment</h1>
        <div class="content-button-container">
          <button class="green-button">Become a volunteer</button
          ><button class="grey-button">Learn more</button>
        </div>
      </div>
    </main>
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
      span {
        height: 40px;
        width: 25%;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      span:nth-child(4) {
        background: #0e6248;
        gap: 3px;
        border-radius: 0.25rem;
      }
    }
  }
  main {
    height: 90vh;
    width: 90%;
    display: flex;
    align-items: center;
    justify-content: center;
    .hero-content {
      width: 50%;
      align-items: center;
      flex-direction: column;
      display: flex;
      height: 40%;
      h1 {
        color: white;
        font-size: 3rem;
        text-align: center;
      }
      .content-button-container {
        width: 50%;
        justify-content: space-evenly;
        display: flex;
        .green-button {
          background: #0e6248;
          padding: 10px 30px;
          outline: none;
          border: none;
          color: white;
          font-family: Lato;
          border-radius: 0.25rem;
        }
        .grey-button {
          outline: none;
          background: #ffffff75;
          padding: 10px 30px;
          border: none;
          color: white;
          border-radius: 0.25rem;
          font-family: Lato;
        }
      }
    }
  }
}
</style>

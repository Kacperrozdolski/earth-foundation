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
        <img src="../assets/hamburger.svg" class="hamburger" />
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
      min-width: 30%;
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
      min-width: 30%;
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
      .hamburger {
        display: none;
      }
      span:nth-child(4) {
        background: #0e6248;
        gap: 3px;
        border-radius: 0.25rem;
      }
    }
  }
  main {
    min-height: 90vh;
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
        min-width: 80%;
        gap: 10px;
        justify-content: space-around;
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
@media only screen and (max-width: 1100px) {
  nav {
    width: 100% !important;
    .center {
      width: auto;
      img {
        height: 60px !important;
      }
      span {
        display: none !important;
      }
    }
  }
  main {
    .hero-content {
      width: 80% !important;
    }
  }
}
@media only screen and (max-width: 800px) {
  nav {
    width: 90% !important;
    align-items: flex-start !important;
    justify-content: space-between !important;
    .left {
      display: none !important;
    }
    .center {
      height: 100%;
      display: flex;
      justify-content: flex-start !important;
      width: auto !important;
    }
    .right {
      height: 100%;
      display: flex;
      justify-content: flex-end;
      align-items: flex-end;
      .hamburger {
        margin-left: auto;
        display: inline !important;
        height: 30px;
      }
      span {
        display: none !important;
      }
    }
  }
  h1 {
    font-size: 2.5rem !important;
    text-align: left !important;
  }
}
</style>

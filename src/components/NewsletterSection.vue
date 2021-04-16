<template>
  <section>
    <div class="newsletter-container">
      <h1>Helps us make more sustainable projects</h1>
      <p>
        Donec turpis sapien, dignissim in augue ac, venenatis interdum justo.
      </p>
      <div class="newsletter-input">
        <input type="text" placeholder="Email" />
        <button>Subscribe</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "",
};
</script>

<style lang="scss" scoped>
section {
  height: 40vh;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  .newsletter-container {
    width: 60%;
    height: 60%;
    background: #0e6248;
    border-radius: 0.75rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    h1 {
      margin: 0;
      font-weight: 900;
    }
    p {
      margin: 0 0 20px 0;
    }
    .newsletter-input {
      width: 40%;
      display: flex;
      input {
        width: 75%;
        height: 30px;
        padding-left: 20px;
        font-style: italic;
        font-family: Lato;
        border-top-left-radius: 0.125rem;
        border-bottom-left-radius: 0.125rem;
        margin: 0;
        border: 0;
        outline: 0;
      }
      button {
        width: 25%;
        color: #0e6248;
        font-family: Lato;
        font-weight: 700;
        background: rgba(255, 255, 255, 0.74);
        margin: 0;
        border: 0;
        border-top-right-radius: 0.125rem;
        border-bottom-right-radius: 0.125rem;
        outline: 0;
      }
    }
  }
}
@media only screen and (max-width: 1100px) {
  .newsletter-container {
    width: 60% !important;
    margin-bottom: 40px;
    .newsletter-input {
      width: 80% !important;
      button {
        min-width: 45% !important;
      }
    }
  }
}
@media only screen and (max-width: 800px) {
  .newsletter-container {
    min-height: 100%;
    width: 95% !important;
    text-align: center;
    .newsletter-input {
      width: 80% !important;
    }
  }
}
</style>

<template>
  <section>
    <div class="reading-container">
      <p>Reading resources</p>
      <div class="container-header">
        <h1>
          Quisque laoreet eros ut elementum molestie. Morbi posuere non ante non
          porta. Vivamus posuere lectus sed urna commodo gravida.
        </h1>
        <div class="button-container">
          <button>Become a partner</button>
        </div>
      </div>
      <div class="card-container">
        <div class="card">
          <h2>Nulla eu rutrum enim</h2>
          <p>
            Ut bibendum sagittis nibh, eget finibus sapien ornare sed. Mauris
            eget elit pharetra neque dictum bibendum at vestibulum sapien. Proin
            sodales, ex ac ornare hendrerit, nulla nisl semper leo
          </p>
          <button>Download</button>
        </div>
        <div class="card">
          <h2>Nulla eu rutrum enim</h2>
          <p>
            Ut bibendum sagittis nibh, eget finibus sapien ornare sed. Mauris
            eget elit pharetra neque dictum bibendum at vestibulum sapien. Proin
            sodales, ex ac ornare hendrerit, nulla nisl semper leo
          </p>
          <button>Download</button>
        </div>
        <div class="card">
          <h2>Nulla eu rutrum enim</h2>
          <p>
            Ut bibendum sagittis nibh, eget finibus sapien ornare sed. Mauris
            eget elit pharetra neque dictum bibendum at vestibulum sapien. Proin
            sodales, ex ac ornare hendrerit, nulla nisl semper leo
          </p>
          <button>Download</button>
        </div>
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
  min-height: 60vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  .reading-container {
    width: 60%;
    min-height: 80%;
    display: flex;
    flex-direction: column;
    p {
      margin: 0;
    }
    .container-header {
      min-height: 20%;
      display: flex;
      width: 100%;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
      h1 {
        margin: 0;
        width: 70%;
        font-weight: 700;
        height: 100%;
      }
      div {
        width: 30%;
        height: 100%;
        display: flex;
        justify-content: flex-end;
        button {
          width: 80%;
          height: 50%;
          background: #0e6248;
          color: white;
          outline: none;
          border: none;
          padding: 10px;
          border-radius: 0.5rem;
          font-weight: 700;
        }
      }
    }
    .card-container {
      height: 80%;
      width: 100%;
      display: flex;
      justify-content: space-between;
      .card {
        width: 30%;
        height: 100%;
        border: 1px solid #dddddd;
        border-radius: 0.5rem;
        display: flex;
        flex-direction: column;
        gap: 5px;
        img {
          width: 100%;
          transform: translate(5px, -20px);
          border-radius: 0.5rem;
        }
        h2 {
          margin: 10px;
        }
        p {
          margin: 10px;
        }
        button {
          width: 40%;
          background: #0e6248;
          color: white;
          outline: none;
          border: none;
          padding: 10px;
          align-self: center;
          font-weight: 700;
          border-radius: 0.5rem;
          margin-bottom: 30px;
        }
      }
    }
  }
}
@media only screen and (max-width: 1100px) {
  .reading-container {
    margin: 30px 0;
    gap: 20px;
    width: 65% !important;
    .card-container {
      flex-direction: column !important;
      gap: 30px;
      .card {
        width: 100% !important;
      }
    }
  }
}
@media only screen and (max-width: 800px) {
  .reading-container {
    width: 95% !important;
    .container-header {
      flex-direction: column;
      gap: 20px;
      h1 {
        width: 100% !important;
      }
      .button-container {
        width: 100% !important;
        justify-content: flex-start !important;
        button {
          width: 40%;
        }
      }
    }
  }
}
</style>

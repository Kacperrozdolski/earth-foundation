<template>
  <section>
    <div class="about-container">
      <p>What we do</p>
      <div class="container-header">
        <h1>
          Our mission is to create sustainable work gravida, tellus sit amet
          pretium auctor, mauris ligula egestas tellus, sed porta erat nunc ut
          ligula.
        </h1>
        <div>
          <button>Become a volunteer</button>
        </div>
      </div>
      <div class="card-container">
        <div class="card">
          <img src="../assets/about_01.png" alt="" srcset="" />
          <h2>Nulla eu rutrum enim</h2>
          <p>
            Ut bibendum sagittis nibh, eget finibus sapien ornare sed. Mauris
            eget elit pharetra neque dictum bibendum at vestibulum sapien. Proin
            sodales, ex ac ornare hendrerit, nulla nisl semper leo
          </p>
          <button>Learn more</button>
        </div>
        <div class="card">
          <img src="../assets/about_02.png" alt="" srcset="" />
          <h2>Nulla eu rutrum enim</h2>
          <p>
            Ut bibendum sagittis nibh, eget finibus sapien ornare sed. Mauris
            eget elit pharetra neque dictum bibendum at vestibulum sapien. Proin
            sodales, ex ac ornare hendrerit, nulla nisl semper leo
          </p>
          <button>Learn more</button>
        </div>
        <div class="card">
          <img src="../assets/about_03.png" alt="" srcset="" />
          <h2>Nulla eu rutrum enim</h2>
          <p>
            Ut bibendum sagittis nibh, eget finibus sapien ornare sed. Mauris
            eget elit pharetra neque dictum bibendum at vestibulum sapien. Proin
            sodales, ex ac ornare hendrerit, nulla nisl semper leo
          </p>
          <button>Learn more</button>
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
  height: 90vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  .about-container {
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
</style>

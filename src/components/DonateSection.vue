<template>
  <section>
    <div class="donate-container">
      <div class="donate-content">
        <h1>
          Want to help? We are always in need of donations, vitae ex quam.
          Quisque nulla purus, elementum eu nunc at, cursus finibus tortor.
        </h1>
        <p>
          Mauris eget elit pharetra neque dictum bibendum at vestibulum sapien.
          Proin sodales, ex ac ornare hendrerit, nulla nisl semper leo.
        </p>
        <p>
          Nulla porta dui non libero viverra mattis a nec velit. Integer nulla
          tellus, dignissim eget posuere a, lobortis in justo. Quisque hendrerit
          egestas neque. Donec turpis sapien, dignissim in augue ac, venenatis
          interdum justo.
        </p>
      </div>
      <div class="donate-form">
        <label for="name">Name:</label>
        <input id="name" type="text" />
        <label for="name">Email:</label>
        <input id="name" type="text" />
        <label for="name">Amount:</label>
        <input id="name" type="text" />
        <button>Donate</button>
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
  min-height: 50vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  .donate-container {
    width: 60%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    .donate-content {
      height: 100%;
      width: 60%;
      margin-bottom: auto;
      h1 {
        margin: 0;
        font-weight: 900;
        font-size: 1.75rem;
      }
    }
    .donate-form {
      min-height: 100%;
      display: flex;
      flex-direction: column;
      width: 35%;
      input {
        margin-bottom: 25px;
        height: 30px;
      }
      label {
        font-weight: 700;
        font-size: 0.75rem;
      }
      button {
        width: 60%;
        height: 50%;
        background: #0e6248;
        color: white;
        outline: none;
        border: none;
        align-self: center;
        padding: 10px;
        border-radius: 0.5rem;
        font-weight: 700;
      }
    }
  }
}
</style>

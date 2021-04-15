<template>
  <section>
    <div class="footer-container">
      <div class="footer-left">
        <h2>Earth Foundation</h2>
        <p>Earth Heart Foundation Cebu © 2020. All rights reserved.</p>
      </div>
      <div class="footer-right">
        <p>Privacy Policy</p>
        <p>Terms & Conditions</p>
        <p>+63 911 111 1111</p>
        <p>Unit 12 Bldg Name, Street Name</p>
        <p>City, Country 4444</p>
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
  background: #272727;
  min-height: 20vh;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  .footer-container {
    width: 60%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    color: white;
    p {
      font-size: 0.75rem;
      text-align: right;
    }
  }
}
</style>

<template>
  <section>
    <p>
      The Earth Heart (EF) is a non-profit organization that aims to assist and
      uplift rural communities in Cebu with the support of various environmental
      projects.
    </p>
  </section>
</template>

<script>
export default {
  name: "",
};
</script>

<style lang="scss" scoped>
section {
  background: #fbf8f6;
  min-height: 15vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  p {
    width: 60%;
    text-align: center;
  }
}
@media only screen and (max-width: 1100px) {
  section {
    p {
      width: 80% !important;
    }
  }
}
@media only screen and (max-width: 800px) {
  section {
    p {
      width: 95% !important;
    }
  }
}
</style>

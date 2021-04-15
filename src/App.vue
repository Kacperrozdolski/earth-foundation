<template>
  <div class="earth-foundation">
    <HeroSection />
  </div>
</template>

<script>
import HeroSection from "./components/HeroSection.vue";
// import AboutSection from "./components/AboutSection.vue";
// import DonateSection from "./components/DonateSection.vue";
// import FooterSection from "./components/FooterSection.vue";
// import GalerySection from "./components/GalerySection.vue";
// import NewsletterSection from "./components/NewsletterSection.vue";
// import ReadingSection from "./components/ReadingSection.vue";
export default {
  name: "App",
  components: { HeroSection },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Lato:wght@100;300;400;700;900&display=swap");
body {
  margin: 0 !important;
  font-family: Lato;
}
.earth-foundation {
  min-height: 100vh;
  width: 100%;
}
</style>

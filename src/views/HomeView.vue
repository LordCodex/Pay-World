<template>
  <div class="home">
    <div class="hero-bg">
      <NavBar />
      <HeroSection />
      <AboutSection />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

import NavBar from "@/components/NavBar.vue";
import HeroSection from "@/components/HeroSection.vue";
import AboutSection from "@/components/AboutSection.vue";

export default {
  name: "HomeView",
  components: {
    NavBar,
    AboutSection,
    HeroSection,
  },
};
</script>

<style></style>

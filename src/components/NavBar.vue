<template>
  <div class="NavBar">
    <div class="nav-section">
      <div class="logo">
        <h1 :class="{ actives: isClicked }">
          <router-link to="/">Payworld.</router-link>
        </h1>
      </div>
      <div class="navlinks">
        <ul :class="{ active: isClicked }">
          <li>Service</li>
          <li>Payment</li>
          <li><router-link to="/about">Company</router-link></li>
          <li>News</li>
        </ul>
      </div>
      <div class="nav-buttons">
        <button class="navbut">Get Started</button>
      </div>
      <div class="hamburger" @click="ToggleHandler">
        <div v-if="(isClicked = isClicked)">
          <i class="fa fa-bars" aria-hidden="true"></i>
        </div>
        <div v-else><i class="fa fa-times" aria-hidden="true"></i></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      isClicked: true,
    };
  },
  methods: {
    ToggleHandler() {
      this.isClicked = !this.isClicked;
      console.log(this.isClicked);
    },
  },
};
</script>

<style>
@import "../assets/css/header.css";
</style>

<template>
  <div class="NavBar">
    <div class="nav-section">
      <div class="logo">
        <h1><router-link to="/">Payworld.</router-link></h1>
      </div>
      <div class="navlinks">
        <ul>
          <li>Service</li>
          <li>Payment</li>
          <li><router-link to="/about">Company</router-link></li>
          <li>News</li>
        </ul>
      </div>
      <div class="nav-buttons">
        <button class="navbut">Get Started</button>
      </div>
      <div class="hamburger">
        <i class="fa fa-bars" aria-hidden="true"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style>
@import "../assets/css/header.css";
</style>

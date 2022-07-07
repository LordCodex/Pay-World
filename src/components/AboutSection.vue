<template>
  <div class="About__section">
    <div class="AboutSection_text">
      <h1>Who We Are</h1>
      <p>
        We are a worldwide technology-driven company focused on payments. <br />
        Our diversified proposition delivers value across the board
      </p>
    </div>
    <div class="About__section__box">
      <div class="sec-box">
        <div class="boxs">
          <img src="../assets/img/verve.png" alt="" />
          <p>Leverage our Technology Expertise to Grow Your Business.</p>
          <h3>Get Started</h3>
        </div>
      </div>
      <div class="sec-box">
        <div class="boxs">
          <img src="../assets/img/quick.png" alt="" />
          <p>Leverage our Technology Expertise to Grow Your Business.</p>
          <h3>Get Started</h3>
        </div>
      </div>
      <div class="sec-box">
        <div class="boxs">
          <img src="../assets/img/quickb.png" alt="" />
          <p>Leverage our Technology Expertise to Grow Your Business.</p>
          <h3>Get Started</h3>
        </div>
      </div>
      <div class="sec-box">
        <div class="boxs">
          <img src="../assets/img/inter.png" alt="" />
          <p>Leverage our Technology Expertise to Grow Your Business.</p>
          <h3>Get Started</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutSection",
};
</script>

<style scoped>
.About__section {
  width: 100%;
  max-width: 80%;
  margin: 0 auto;
}
.AboutSection_text {
  text-align: center;
  padding: 1em 0;
  line-height: 1.5;
}
.About__section__box {
  padding: 2em;
  /* background-color: red;
  border: 1px solid black; */
  display: flex;
  align-items: center;
  gap: 2em;
  justify-content: center;
}
.sec-box {
  padding: 1em;
  /* background-color: blue; */
  box-shadow: rgba(0, 0, 0, 0.25) 0px 14px 28px,
    rgba(0, 0, 0, 0.22) 0px 10px 10px;
  border-radius: 0.5em;
}
.boxs {
  display: flex;
  flex-direction: column;
  gap: 1em;
  text-align: center;
}
</style>

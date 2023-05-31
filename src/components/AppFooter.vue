<template>
  <div>
    <div class="footer-bg justify-center">
      <div class="footer-text" style="margin: auto; padding-top: 8rem">
        <img
          src="src/assets/images/logo-restaurant-2x.png"
          alt=""
          style="height: 50px"
        />
        <p>
          Qual eu proinsulina sit massa condimentum. Volutpat non pulvinar
          aliquet nunc. Quai eu proie sit massa condimmentum.
        </p>
        <div class="justify-center d-flex" style="padding-left: 10rem">
          <div
            class="social-icon justify-center"
            v-for="(icon, i) in socialIcons"
            :key="i"
          >
            <i :class="icon"></i>
          </div>
        </div>
      </div>
    </div>
    <div class="end-footer">
      <p>
        &copy; Copyright 2012 - 2022 | Avada Theme by
        <a href="">ThemeFusion</a> | All Rights Reserved | Powered by
        <a href="">WordPress</a>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      socialIcons: [
        "fab fa-facebook-f",
        "fab fa-twitter",
        "fab fa-youtube",
        "fab fa-instagram",
        "fab fa-linkedin-in",
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../styles/_variables.scss";
.footer-bg {
  position: relative;
  width: 100%;
  height: 600px;
  background-image: url(../assets/images/footer2x.jpg);
  background-size: cover;
  .footer-text {
    text-align: center;
    color: $second-color;
    width: 600px;
    p {
      margin: 40px 0;
      font-size: 20px;
    }
    .social-icon {
      display: flex;
      align-items: center;
      padding-left: 17px;
      cursor: pointer;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background-color: $second-color;
      color: $first-color;
      transition: all 1s;
      margin: 0 5px;
      &:hover {
        background-color: rgba(0, 0, 0, 0.8);
        color: $second-color;
        transition: all 0.3s;
      }
    }
  }
}

.end-footer {
  height: 80px;
  width: 100%;
  background-color: $first-color;
  color: $third-color;
  p {
    font-size: 12px;
    text-align: center;
    line-height: 80px;
    a {
      text-decoration: none;
      color: $second-color;
    }
  }
}
</style>

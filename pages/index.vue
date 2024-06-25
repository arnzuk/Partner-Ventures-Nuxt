<template>
  <div class="landing-page-container">
    <div class="landing-page-top-container">
      <h1 class="landing-page-logo">Dembovskij &amp; Žukauskas</h1>
      <div class="landing-page-links-container">
        <span class="landing-page-text">
          <span class="landing-page-text1">Home</span>
          <span>  /</span>
        </span>
        <span class="landing-page-text3">Consulting  /</span>
        <span class="landing-page-text4">Solutions  /</span>
        <span class="landing-page-text5">Contact</span>
      </div>
      <h1 class="landing-page-text6">Partner Ventures</h1>
    </div>
    <about-us rootClassName="about-us-root-class-name"></about-us>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AboutUs from '../components/about-us'
import AppFooter from '../components/footer'

export default {
  name: 'LandingPage',
  props: {},
  components: {
    AboutUs,
    AppFooter,
  },
  head: {
    title: 'Partner Ventures',
    meta: [
      {
        property: 'og:title',
        content: 'Partner Ventures',
      },
    ],
  },
}
</script>

<style scoped>
.landing-page-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.landing-page-top-container {
  width: 100%;
  height: 659px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  background-size: cover;
  justify-content: center;
  background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-1500w.jpg");
  background-position: 0% 40%;
}
.landing-page-logo {
  top: 108px;
  left: 269px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-style: normal;
  font-family: "Noto Sans";
  font-weight: 700;
}
.landing-page-links-container {
  top: 125px;
  left: 1426px;
  width: 543px;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.landing-page-text {
  top: 0px;
  left: 302px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.landing-page-text1 {
  text-decoration: underline;
}
.landing-page-text3 {
  top: 0px;
  left: 372px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.landing-page-text4 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -16px;
  position: absolute;
  font-family: "Noto Sans";
}
.landing-page-text5 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -78px;
  position: absolute;
  font-family: "Noto Sans";
}
.landing-page-text6 {
  top: 345px;
  left: 935px;
  color: rgb(255, 255, 255);
  width: 681px;
  height: 108px;
  position: absolute;
  font-size: 76px;
  font-family: "Noto Sans";
}
@media(max-width: 2560px) {
  .landing-page-top-container {
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-1500w.jpg");
  }
  .landing-page-text6 {
    top: 308px;
    left: 564px;
  }
}
@media(max-width: 1920px) {
  .landing-page-logo {
    top: 137px;
    left: 231px;
  }
  .landing-page-links-container {
    top: 150px;
    left: 1019px;
  }
  .landing-page-text5 {
    top: 0px;
    right: -79px;
  }
  .landing-page-text6 {
    top: 346px;
    left: 695px;
  }
}
@media(max-width: 1200px) {
  .landing-page-top-container {
    height: 491px;
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-1500w.jpg");
  }
  .landing-page-logo {
    top: 99px;
    left: 91px;
    color: #ffffff;
  }
  .landing-page-links-container {
    top: 120px;
    left: 643px;
    width: 393px;
    height: 31px;
    position: absolute;
  }
  .landing-page-text {
    top: 1px;
    left: 73px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .landing-page-text3 {
    top: 0px;
    left: 142px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .landing-page-text4 {
    top: 0px;
    left: 243px;
    color: rgb(255, 255, 255);
    right: 0px;
    position: absolute;
    font-family: Noto Sans;
  }
  .landing-page-text5 {
    top: 0px;
    color: rgb(255, 255, 255);
    right: 4px;
    position: absolute;
    font-family: Noto Sans;
  }
  .landing-page-text6 {
    top: 294px;
    left: 413px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-size: 46px;
    font-family: Georgia;
  }
}
@media(max-width: 990px) {
  .landing-page-links-container {
    top: 172px;
    left: 415px;
    position: absolute;
  }
  .landing-page-text6 {
    top: 293px;
    left: 231px;
    position: absolute;
  }
}
@media(max-width: 767px) {
  .landing-page-links-container {
    top: 175px;
    left: 289px;
  }
}
@media(max-width: 479px) {
  .landing-page-links-container {
    top: 206px;
    left: 23px;
  }
  .landing-page-text6 {
    left: 30px;
    bottom: 51px;
  }
}
</style>

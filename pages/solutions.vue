<template>
  <div class="solutions-container">
    <div class="solutions-top-container">
      <h1 class="solutions-logo">Dembovskij &amp; Žukauskas</h1>
      <div class="solutions-links-container">
        <span class="solutions-text">
          <span>Home</span>
          <span>  /</span>
        </span>
        <span class="solutions-text3">Consulting  /</span>
        <span class="solutions-text4">
          <span class="solutions-text5">Solutions</span>
          <span>  /</span>
        </span>
        <span class="solutions-text7">Contact</span>
      </div>
      <h1 class="solutions-text8">Partner Ventures</h1>
    </div>
    <solutions-products></solutions-products>
    <app-footer></app-footer>
  </div>
</template>

<script>
import SolutionsProducts from '../components/solutions-products'
import AppFooter from '../components/footer'

export default {
  name: 'Solutions',
  props: {},
  components: {
    SolutionsProducts,
    AppFooter,
  },
  head: {
    title: 'Solutions - Partner Ventures',
    meta: [
      {
        property: 'og:title',
        content: 'Solutions - Partner Ventures',
      },
    ],
  },
}
</script>

<style scoped>
.solutions-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.solutions-top-container {
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
.solutions-logo {
  top: 108px;
  left: 269px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-style: normal;
  font-family: "Noto Sans";
  font-weight: 700;
}
.solutions-links-container {
  top: 125px;
  left: 1426px;
  width: 543px;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.solutions-text {
  top: 0px;
  left: 302px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.solutions-text3 {
  top: 0px;
  left: 372px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.solutions-text4 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -16px;
  position: absolute;
  font-family: "Noto Sans";
}
.solutions-text5 {
  text-decoration: underline;
}
.solutions-text7 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -78px;
  position: absolute;
  font-family: "Noto Sans";
}
.solutions-text8 {
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
  .solutions-top-container {
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-1500w.jpg");
  }
  .solutions-text8 {
    top: 308px;
    left: 564px;
  }
}
@media(max-width: 1920px) {
  .solutions-logo {
    top: 137px;
    left: 231px;
  }
  .solutions-links-container {
    top: 150px;
    left: 1019px;
  }
  .solutions-text7 {
    top: 0px;
    right: -79px;
  }
  .solutions-text8 {
    top: 346px;
    left: 695px;
  }
}
@media(max-width: 1200px) {
  .solutions-top-container {
    height: 491px;
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-1500w.jpg");
  }
  .solutions-logo {
    top: 99px;
    left: 91px;
    color: #ffffff;
  }
  .solutions-links-container {
    top: 120px;
    left: 643px;
    width: 393px;
    height: 31px;
    position: absolute;
  }
  .solutions-text {
    top: 1px;
    left: 73px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .solutions-text3 {
    top: 0px;
    left: 142px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .solutions-text4 {
    top: 0px;
    left: 243px;
    color: rgb(255, 255, 255);
    right: 0px;
    position: absolute;
    font-family: Noto Sans;
  }
  .solutions-text7 {
    top: 0px;
    color: rgb(255, 255, 255);
    right: 4px;
    position: absolute;
    font-family: Noto Sans;
  }
  .solutions-text8 {
    top: 294px;
    left: 413px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-size: 46px;
    font-family: Georgia;
  }
}
@media(max-width: 990px) {
  .solutions-links-container {
    top: 172px;
    left: 415px;
    position: absolute;
  }
  .solutions-text8 {
    top: 293px;
    left: 231px;
    position: absolute;
  }
}
@media(max-width: 767px) {
  .solutions-links-container {
    top: 175px;
    left: 289px;
  }
}
@media(max-width: 479px) {
  .solutions-links-container {
    top: 206px;
    left: 23px;
  }
  .solutions-text8 {
    left: 30px;
    bottom: 51px;
  }
}
</style>

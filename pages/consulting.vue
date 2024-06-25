<template>
  <div class="consulting-container">
    <div class="consulting-top-container">
      <h1 class="consulting-logo">Dembovskij &amp; Žukauskas</h1>
      <div class="consulting-links-container">
        <span class="consulting-text">
          <span>Home</span>
          <span>  /</span>
        </span>
        <span class="consulting-text3">
          <span class="consulting-text4">Consulting</span>
          <span>  /</span>
        </span>
        <span class="consulting-text6">Solutions  /</span>
        <span class="consulting-text7">Contact</span>
      </div>
      <h1 class="consulting-text8">Partner Ventures</h1>
    </div>
    <consulting-services></consulting-services>
    <app-footer></app-footer>
  </div>
</template>

<script>
import ConsultingServices from '../components/consulting-services'
import AppFooter from '../components/footer'

export default {
  name: 'Consulting',
  props: {},
  components: {
    ConsultingServices,
    AppFooter,
  },
  head: {
    title: 'Consulting - Partner Ventures',
    meta: [
      {
        property: 'og:title',
        content: 'Consulting - Partner Ventures',
      },
    ],
  },
}
</script>

<style scoped>
.consulting-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.consulting-top-container {
  width: 100%;
  height: 718px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  background-size: cover;
  justify-content: center;
  background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-800h.jpg");
  background-position: 0% 40%;
}
.consulting-logo {
  top: 69px;
  left: 275px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-style: normal;
  font-family: "Noto Sans";
  font-weight: 700;
}
.consulting-links-container {
  top: 110px;
  left: 1424px;
  width: 543px;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.consulting-text {
  top: 0px;
  left: 302px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.consulting-text3 {
  top: 0px;
  left: 372px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.consulting-text4 {
  text-decoration: underline;
}
.consulting-text6 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -16px;
  position: absolute;
  font-family: "Noto Sans";
}
.consulting-text7 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -78px;
  position: absolute;
  font-family: "Noto Sans";
}
.consulting-text8 {
  top: 380px;
  left: 943px;
  color: rgb(255, 255, 255);
  width: 681px;
  height: 108px;
  position: absolute;
  font-size: 76px;
  font-family: "Noto Sans";
}
@media(max-width: 2560px) {
  .consulting-top-container {
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-800h.jpg");
  }
  .consulting-text8 {
    top: 308px;
    left: 564px;
  }
}
@media(max-width: 1920px) {
  .consulting-logo {
    top: 137px;
    left: 231px;
  }
  .consulting-links-container {
    top: 150px;
    left: 1019px;
  }
  .consulting-text7 {
    top: 0px;
    right: -79px;
  }
  .consulting-text8 {
    top: 346px;
    left: 695px;
  }
}
@media(max-width: 1200px) {
  .consulting-top-container {
    height: 491px;
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-800h.jpg");
  }
  .consulting-logo {
    top: 99px;
    left: 91px;
    color: #ffffff;
  }
  .consulting-links-container {
    top: 120px;
    left: 643px;
    width: 393px;
    height: 31px;
    position: absolute;
  }
  .consulting-text {
    top: 1px;
    left: 73px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .consulting-text3 {
    top: 0px;
    left: 142px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .consulting-text6 {
    top: 0px;
    left: 243px;
    color: rgb(255, 255, 255);
    right: 0px;
    position: absolute;
    font-family: Noto Sans;
  }
  .consulting-text7 {
    top: 0px;
    color: rgb(255, 255, 255);
    right: 4px;
    position: absolute;
    font-family: Noto Sans;
  }
  .consulting-text8 {
    top: 294px;
    left: 413px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-size: 46px;
    font-family: Georgia;
  }
}
@media(max-width: 990px) {
  .consulting-links-container {
    top: 172px;
    left: 415px;
    position: absolute;
  }
  .consulting-text8 {
    top: 293px;
    left: 231px;
    position: absolute;
  }
}
@media(max-width: 767px) {
  .consulting-links-container {
    top: 175px;
    left: 289px;
  }
}
@media(max-width: 479px) {
  .consulting-links-container {
    top: 206px;
    left: 23px;
  }
  .consulting-text8 {
    left: 30px;
    bottom: 51px;
  }
}
</style>

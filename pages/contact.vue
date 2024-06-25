<template>
  <div class="contact-container">
    <div class="contact-top-container">
      <h1 class="contact-logo">Dembovskij &amp; Žukauskas</h1>
      <div class="contact-links-container">
        <span class="contact-text">
          <span>Home</span>
          <span>  /</span>
        </span>
        <span class="contact-text3">Consulting  /</span>
        <span class="contact-text4">Solutions  /</span>
        <span class="contact-text5">Contact</span>
      </div>
      <h1 class="contact-text6">Partner Ventures</h1>
    </div>
    <contact-form10></contact-form10>
    <app-footer></app-footer>
  </div>
</template>

<script>
import ContactForm10 from '../components/contact-form10'
import AppFooter from '../components/footer'

export default {
  name: 'Contact',
  props: {},
  components: {
    ContactForm10,
    AppFooter,
  },
  head: {
    title: 'Contact - Partner Ventures',
    meta: [
      {
        property: 'og:title',
        content: 'Contact - Partner Ventures',
      },
    ],
  },
}
</script>

<style scoped>
.contact-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.contact-top-container {
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
.contact-logo {
  top: 108px;
  left: 269px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-style: normal;
  font-family: "Noto Sans";
  font-weight: 700;
}
.contact-links-container {
  top: 125px;
  left: 1426px;
  width: 543px;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.contact-text {
  top: 0px;
  left: 302px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.contact-text3 {
  top: 0px;
  left: 372px;
  color: rgb(255, 255, 255);
  position: absolute;
  font-family: "Noto Sans";
}
.contact-text4 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -16px;
  position: absolute;
  font-family: "Noto Sans";
}
.contact-text5 {
  top: 0px;
  color: rgb(255, 255, 255);
  right: -78px;
  position: absolute;
  font-family: "Noto Sans";
  text-decoration: underline;
}
.contact-text6 {
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
  .contact-top-container {
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-1500w.jpg");
  }
  .contact-text6 {
    top: 308px;
    left: 564px;
  }
}
@media(max-width: 1920px) {
  .contact-logo {
    top: 137px;
    left: 231px;
  }
  .contact-links-container {
    top: 150px;
    left: 1019px;
  }
  .contact-text5 {
    top: 0px;
    right: -79px;
  }
  .contact-text6 {
    top: 346px;
    left: 695px;
  }
}
@media(max-width: 1200px) {
  .contact-top-container {
    height: 491px;
    background-size: cover;
    background-image: url("/2018.04.30__21.25.39_4.5mm_f2.8_0.33s_iso400_acr_panorama_crop2000-1500w.jpg");
  }
  .contact-logo {
    top: 99px;
    left: 91px;
    color: #ffffff;
  }
  .contact-links-container {
    top: 120px;
    left: 643px;
    width: 393px;
    height: 31px;
    position: absolute;
  }
  .contact-text {
    top: 1px;
    left: 73px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .contact-text3 {
    top: 0px;
    left: 142px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-family: Noto Sans;
  }
  .contact-text4 {
    top: 0px;
    left: 243px;
    color: rgb(255, 255, 255);
    right: 0px;
    position: absolute;
    font-family: Noto Sans;
  }
  .contact-text5 {
    top: 0px;
    color: rgb(255, 255, 255);
    right: 4px;
    position: absolute;
    font-family: Noto Sans;
  }
  .contact-text6 {
    top: 294px;
    left: 413px;
    color: rgb(255, 255, 255);
    position: absolute;
    font-size: 46px;
    font-family: Georgia;
  }
}
@media(max-width: 990px) {
  .contact-links-container {
    top: 172px;
    left: 415px;
    position: absolute;
  }
  .contact-text6 {
    top: 293px;
    left: 231px;
    position: absolute;
  }
}
@media(max-width: 767px) {
  .contact-links-container {
    top: 175px;
    left: 289px;
  }
}
@media(max-width: 479px) {
  .contact-links-container {
    top: 206px;
    left: 23px;
  }
  .contact-text6 {
    left: 30px;
    bottom: 51px;
  }
}
</style>

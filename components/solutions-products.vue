<template>
  <div class="solutions-products-container thq-section-padding">
    <div
      class="solutions-products-max-width thq-section-max-width thq-flex-column"
    >
      <div class="solutions-products-content thq-flex-column">
        <img :alt="imageAlt" :src="imageSrc" class="solutions-products-image" />
        <ul class="solutions-products-ul">
          <li class="solutions-products-li thq-flex-column list-item">
            <h2 class="solutions-products-heading1 thq-heading-2">
              Our Solutions and Products
            </h2>
            <p class="solutions-products-content1 thq-body-small">
              <span>
                       Our own created products in use by Nations and Companies.
              </span>
              <br />
            </p>
            <ul class="solutions-products-ul1 thq-flex-column">
              <li class="solutions-products-li1 list-item">
                <h3 class="solutions-products-heading2 thq-heading-3">
                  Uslugitu.pl
                </h3>
                <p class="solutions-products-content2 thq-body-small">
                  <span>
                    Innovative client and request board for service providers and
                    suppliers. Product connects various request,
                    <span v-html="rawskzn"></span>
                  </span>
                  <br />
                  <span>
                    makes it easy to find buyers, provide value for where it is
                    required the most. Platform creates first in class level of
                    lead control for service providers and professionals in Nation
                    as whole. Platform base it self can be used in different
                    countries, small changes required only, locale, specific
                    categories fine tuning.
                  </span>
                </p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
    <img
      :alt="imageAlt1"
      src="/logo-200h.png"
      class="solutions-products-image1"
    />
  </div>
</template>

<script>
export default {
  name: 'SolutionsProducts',
  props: {
    imageSrc: {
      type: String,
      default: '/uslugitu%20icon-300h.jpg',
    },
    imageSrc1: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    rootClassName: String,
    imageAlt: {
      type: String,
      default: 'image',
    },
    imageAlt1: {
      type: String,
      default: 'image',
    },
  },
  data() {
    return {
      rawskzn: ' ',
    }
  },
}
</script>

<style scoped>
.solutions-products-container {
  width: 100%;
  height: 582px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.solutions-products-max-width {
  width: 100%;
  display: flex;
  max-width: 1400px;
  align-items: center;
  flex-direction: column;
}
.solutions-products-content {
  align-self: stretch;
  align-items: flex-start;
  flex-direction: row;
  justify-content: flex-start;
}
.solutions-products-image {
  top: 114px;
  right: 84px;
  width: 279px;
  height: 211px;
  position: absolute;
  object-fit: cover;
}
.solutions-products-ul {
  width: 1277px;
  height: 578px;
  align-self: flex-end;
}
.solutions-products-li {
  width: 100%;
  height: 100%;
  align-items: flex-start;
}
.solutions-products-heading1 {
  align-self: flex-start;
  font-family: "Noto Sans";
}
.solutions-products-content1 {
  font-family: "Noto Sans";
  margin-bottom: var(--dl-space-space-quadruple);
}
.solutions-products-ul1 {
  height: 140px;
  align-items: flex-start;
  padding-left: 20px;
}
.solutions-products-li1 {
  width: 1014px;
}
.solutions-products-heading2 {
  font-family: "Noto Sans";
}
.solutions-products-content2 {
  font-family: "Noto Sans";
}
.solutions-products-image1 {
  top: 216px;
  left: 1780px;
  width: 113px;
  height: 79px;
  position: absolute;
  object-fit: cover;
}
@media(max-width: 1920px) {
  .solutions-products-content {
    position: relative;
  }
  .solutions-products-image {
    top: 145px;
    left: 1100px;
    right: 138px;
    width: 242px;
    height: 189px;
    position: absolute;
  }
  .solutions-products-image1 {
    top: 230px;
    left: 1500px;
    width: 100px;
    height: 71px;
  }
}
@media(max-width: 1200px) {
  .solutions-products-container {
    height: 500px;
  }
  .solutions-products-max-width {
    height: 658px;
  }
  .solutions-products-content {
    height: 456px;
    position: relative;
  }
  .solutions-products-image {
    top: 99px;
    left: 900px;
    right: 74px;
    width: 239px;
    height: 179px;
  }
  .solutions-products-ul {
    width: 1200px;
    height: 450px;
    position: relative;
  }
  .solutions-products-li {
    width: 1200px;
    height: 100%;
  }
  .solutions-products-heading1 {
    margin-left: 20px;
  }
  .solutions-products-content1 {
    margin-left: 40px;
    margin-bottom: var(--dl-space-space-doubleunit);
  }
  .solutions-products-ul1 {
    width: 100%;
    position: relative;
  }
  .solutions-products-li1 {
    width: 928px;
    height: 160px;
  }
  .solutions-products-heading2 {
    padding-left: 20px;
  }
  .solutions-products-content2 {
    width: 858px;
    font-family: Noto Sans;
    margin-left: 20px;
    margin-right: 20px;
  }
  .solutions-products-image1 {
    top: 193px;
    left: 1038px;
    right: 54px;
    width: 102px;
    height: 68px;
  }
}
@media(max-width: 990px) {
  .solutions-products-image {
    left: 720px;
    width: 232px;
    height: 155px;
  }
  .solutions-products-ul {
    width: 990px;
  }
  .solutions-products-li {
    width: 100%;
  }
  .solutions-products-content1 {
    width: 788px;
    height: 31px;
  }
  .solutions-products-ul1 {
    width: 100%;
    height: 193px;
    padding-left: 0px;
    padding-bottom: 0px;
  }
  .solutions-products-li1 {
    width: 731px;
    height: 100%;
  }
  .solutions-products-content2 {
    width: 693px;
    height: 154px;
    font-family: Noto Sans;
  }
  .solutions-products-image1 {
    top: 202px;
    left: 858px;
    right: 43px;
    width: 91px;
    height: 66px;
    margin-left: 0px;
  }
}
@media(max-width: 767px) {
  .solutions-products-container {
    height: 722px;
    padding-bottom: 0px;
  }
  .solutions-products-max-width {
    height: 100%;
  }
  .solutions-products-content {
    height: 719px;
  }
  .solutions-products-image {
    top: 176px;
    left: 458px;
    width: 237px;
    height: 193px;
  }
  .solutions-products-ul {
    width: 767px;
    height: 100%;
  }
  .solutions-products-li {
    top: -2px;
    right: 5px;
    width: 767px;
    height: 722px;
    position: absolute;
  }
  .solutions-products-content1 {
    height: 80px;
    margin-left: 19px;
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .solutions-products-ul1 {
    width: 100%;
    height: 255px;
    padding-right: 2px;
    padding-bottom: 0px;
  }
  .solutions-products-li1 {
    width: 466px;
  }
  .solutions-products-heading2 {
    padding-left: 20px;
  }
  .solutions-products-content2 {
    width: 440px;
    height: 213px;
    font-family: Noto Sans;
  }
  .solutions-products-image1 {
    top: 270px;
    left: 590px;
    right: 66px;
    width: 106px;
    height: 85px;
  }
}
@media(max-width: 479px) {
  .solutions-products-container {
    height: 661px;
    margin-bottom: 4px;
  }
  .solutions-products-max-width {
    height: 100%;
  }
  .solutions-products-content {
    height: 1150px;
  }
  .solutions-products-image {
    top: 180px;
    left: 160px;
    right: 25px;
    width: 294px;
    height: 205px;
  }
  .solutions-products-ul {
    width: 479px;
    height: 100%;
  }
  .solutions-products-li {
    width: 479px;
    height: 1150px;
  }
  .solutions-products-content1 {
    width: 456px;
    height: 85px;
    padding-bottom: 0px;
  }
  .solutions-products-ul1 {
    width: 100%;
    height: 505px;
    padding-top: 177px;
    padding-left: 20px;
  }
  .solutions-products-li1 {
    width: 459px;
    height: 100%;
  }
  .solutions-products-content2 {
    width: 435px;
    height: 285px;
    font-family: Noto Sans;
    padding-left: 0px;
  }
  .solutions-products-image1 {
    top: 300px;
    left: 334px;
    right: 27px;
    width: 115px;
    height: 81px;
    position: absolute;
  }
}
</style>

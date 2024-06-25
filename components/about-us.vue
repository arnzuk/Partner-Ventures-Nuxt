<template>
  <div
    class="about-us-container thq-section-padding"
    v-bind:class="rootClassName"
  >
    <div class="about-us-max-width thq-section-max-width thq-flex-column">
      <div class="about-us-content thq-flex-column">
        <ul class="about-us-ul">
          <li class="about-us-li thq-flex-column list-item">
            <h2 class="about-us-heading1 thq-heading-2">About us</h2>
            <p class="about-us-content1 thq-body-small">
              <span>
                        Partner Ventures is Tech and IT company based in Vilnius,
                Lithuania. We started as two partners coming together to solve
                technical problems in IT products, providing value with
                optimizations and effective executions. We come to bring practical
                Tech and IT innovations in daily life for business and consumers. 
              </span>
              <br />
              <span>
                Ever encounter lack of service, frustration with problem in need
                of a solution, optimization, making something more efficient?
              </span>
              <br />
              <span>
                Technical systems in dire need of optimizations, niche IT
                solutions, small businesses requiring empowerment through
                technical and IT tools.
              </span>
              <br />
              <span>
                We create value for our clients with simple and elegant IT
                products, specialized for every need and pain point.
              </span>
              <br />
            </p>
            <ul class="about-us-ul1 thq-flex-column">
              <li class="list-item">
                <h3 class="about-us-heading2 thq-heading-3">Our Products</h3>
                <p class="about-us-content2 thq-body-small">
                  <span>
                    Uslugitu.pl - Services and work board web application for
                    connecting specialists, service providers with clients and
                    requestor. System covers current market needs such as lack of
                    customer request and lead control, long and complicated
                    request creation process, complex pricing methods.
                  </span>
                  <br />
                  <span>
                    One form for quick request creation, make client visible for
                    provider, let interested service providers find client
                    themselves, provide control tools for suppliers and providers,
                    uncomplicated and standardized payments.
                  </span>
                  <br />
                </p>
              </li>
            </ul>
          </li>
        </ul>
        <img :alt="imageAlt1" :src="imageSrc1" class="about-us-image" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutUs',
  props: {
    imageAlt1: {
      type: String,
      default: 'image',
    },
    rootClassName: String,
    imageSrc: {
      type: String,
      default: '37c38e1d-eaa7-41c4-8bb3-1eae396ae2a7',
    },
    imageSrc1: {
      type: String,
      default: '/logo-200h.png',
    },
  },
}
</script>

<style scoped>
.about-us-container {
  width: 100%;
  height: 364px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.about-us-max-width {
  width: 100%;
  display: flex;
  max-width: 1400px;
  align-items: center;
  flex-direction: column;
}
.about-us-content {
  align-self: stretch;
  align-items: flex-start;
}
.about-us-ul {
  width: 1277px;
  align-self: flex-end;
}
.about-us-li {
  height: 369px;
  align-items: flex-start;
}
.about-us-heading1 {
  align-self: flex-start;
  font-family: "Noto Sans";
}
.about-us-content1 {
  font-family: "Noto Sans";
  margin-bottom: var(--dl-space-space-halfunit);
}
.about-us-ul1 {
  align-items: flex-start;
  padding-left: 120px;
}
.about-us-heading2 {
  font-family: "Noto Sans";
}
.about-us-content2 {
  font-family: "Noto Sans";
}
.about-us-image {
  top: 218px;
  left: 88px;
  width: 134px;
  height: 103px;
  position: absolute;
  object-fit: cover;
}

.about-us-root-class-name1 {
  height: 450px;
}


@media(max-width: 1920px) {
  .about-us-image {
    top: 222px;
    left: 120px;
    width: 108px;
    height: 88px;
  }
}
@media(max-width: 1200px) {
  .about-us-container {
    height: 414px;
  }
  .about-us-content {
    position: relative;
  }
  .about-us-ul {
    width: 1200px;
    height: 450px;
    position: relative;
  }
  .about-us-li {
    width: 1200px;
    height: 678px;
  }
  .about-us-heading1 {
    margin-left: 20px;
  }
  .about-us-content1 {
    margin-left: 40px;
    margin-bottom: var(--dl-space-space-doubleunit);
  }
  .about-us-ul1 {
    position: relative;
  }
  .about-us-content2 {
    margin-left: 20px;
    margin-right: 20px;
  }
  .about-us-image {
    top: 270px;
    left: 22px;
    bottom: -25px;
    position: absolute;
  }
}
@media(max-width: 990px) {
  .about-us-ul {
    width: 990px;
  }
  .about-us-li {
    width: 100%;
  }
  .about-us-content2 {
    font-family: Noto Sans;
  }
  .about-us-image {
    top: 290px;
    left: 60px;
    width: 66px;
    bottom: 4px;
    height: 58px;
    position: absolute;
  }
}
@media(max-width: 767px) {
  .about-us-container {
    height: 540px;
  }
  .about-us-max-width {
    height: 538px;
  }
  .about-us-content {
    height: 556px;
  }
  .about-us-ul {
    width: 767px;
    height: 100%;
  }
  .about-us-li {
    top: -2px;
    right: 5px;
    width: 767px;
    height: 539px;
    position: absolute;
  }
  .about-us-image {
    top: 361px;
    left: 55px;
  }
}
@media(max-width: 479px) {
  .about-us-container {
    height: 823px;
  }
  .about-us-max-width {
    height: 100%;
  }
  .about-us-content {
    height: 833px;
  }
  .about-us-ul {
    width: 479px;
    height: 810px;
  }
  .about-us-li {
    width: 479px;
    height: 828px;
  }
  .about-us-image {
    top: 463px;
    left: 53px;
  }
}
</style>

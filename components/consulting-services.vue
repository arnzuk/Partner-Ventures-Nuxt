<template>
  <div class="consulting-services-container thq-section-padding">
    <div
      class="consulting-services-max-width thq-section-max-width thq-flex-column"
    >
      <div class="consulting-services-content thq-flex-column">
        <ul class="consulting-services-ul">
          <li class="consulting-services-li thq-flex-column list-item">
            <h2 class="consulting-services-heading1 thq-heading-2">
              Consulting Services
            </h2>
            <p class="consulting-services-content1 thq-body-small">
              <span>
                       
                <span v-html="raw8w5i"></span>
              </span>
              <span>
                We provide consultations for small to nation-wide business in
                incorporating technical and IT solutions to everyday task, such as
                infrastructure management,
              </span>
              <br />
              <span>
                work and delegation, effective classification and process
                execution.
              </span>
              <br />
            </p>
            <ul class="consulting-services-ul1 thq-flex-column">
              <li class="list-item">
                <h3 class="consulting-services-heading2 thq-heading-3">
                  Process analysis
                </h3>
                <p class="consulting-services-content2 thq-body-small">
                  We work together with you to research and analyze your current
                  business actions , processes and help you in describing,
                  detailing and having crystal clear processes, procedures and
                  business diagrams. Things which are foundation for any company
                  looking to expand or double down on cost analysis and operation
                  savings.
                </p>
              </li>
            </ul>
            <ul class="consulting-services-ul2 thq-flex-column">
              <li class="list-item">
                <h3 class="consulting-services-heading21 thq-heading-3">
                  Effective work management
                </h3>
                <p class="consulting-services-content21 thq-body-small">
                  Procedures with too many steps or levels hinder effective and
                  lean task, project completion, working closely with you, we can
                  provide IT tools and solutions tailored for your needs with less
                  steps and more data for business intelligence.
                </p>
              </li>
            </ul>
            <ul class="consulting-services-ul3 thq-flex-column">
              <li class="list-item">
                <h3 class="consulting-services-heading22 thq-heading-3">
                  Technical IT solution realization
                </h3>
                <p class="consulting-services-content22 thq-body-small">
                  Well known brands and IT systems are not well adapted to you
                  exact needs or requirements, we can be third party which will
                  help you and supplier in providing best value while not losing
                  track of scope, price or time. We can help detailing and
                  customizing complex solutions to cover client needs all the
                  while being support you need in working with suppliers.
                </p>
              </li>
            </ul>
            <ul class="consulting-services-ul4 thq-flex-column">
              <li class="list-item">
                <h3 class="consulting-services-heading23 thq-heading-3">
                  Solution creation
                </h3>
                <p class="consulting-services-content23 thq-body-small">
                  We can be the ones who are understanding and flexible around
                  your needs in providing best in class value for your company
                  with tool and solutions covering your business needs, be it
                  work, asset management, data collection and analysis or
                  integrations between.
                </p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ConsultingServices',
  props: {
    imageAlt1: {
      type: String,
      default: 'image',
    },
    rootClassName: String,
    imageSrc1: {
      type: String,
      default: '776ea6e0-e1bd-45c0-8b72-755dc215b7da',
    },
  },
  data() {
    return {
      raw8w5i: ' ',
    }
  },
}
</script>

<style scoped>
.consulting-services-container {
  width: 100%;
  height: 575px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.consulting-services-max-width {
  width: 100%;
  display: flex;
  max-width: 1400px;
  align-items: center;
  flex-direction: column;
}
.consulting-services-content {
  align-self: stretch;
  align-items: flex-start;
}
.consulting-services-ul {
  width: 1277px;
  height: 578px;
  align-self: flex-end;
}
.consulting-services-li {
  height: 100%;
  align-items: flex-start;
}
.consulting-services-heading1 {
  align-self: flex-start;
  font-family: "Noto Sans";
}
.consulting-services-content1 {
  font-family: "Noto Sans";
  margin-bottom: var(--dl-space-space-halfunit);
}
.consulting-services-ul1 {
  height: 140px;
  align-items: flex-start;
  padding-left: 120px;
}
.consulting-services-heading2 {
  font-family: "Noto Sans";
}
.consulting-services-content2 {
  font-family: "Noto Sans";
}
.consulting-services-ul2 {
  height: 106px;
  align-items: flex-start;
  padding-left: 120px;
}
.consulting-services-heading21 {
  font-family: "Noto Sans";
}
.consulting-services-content21 {
  font-family: "Noto Sans";
}
.consulting-services-ul3 {
  height: 138px;
  align-items: flex-start;
  padding-left: 120px;
}
.consulting-services-heading22 {
  font-family: "Noto Sans";
}
.consulting-services-content22 {
  font-family: "Noto Sans";
}
.consulting-services-ul4 {
  height: 138px;
  align-items: flex-start;
  padding-left: 120px;
}
.consulting-services-heading23 {
  font-family: "Noto Sans";
}
.consulting-services-content23 {
  font-family: "Noto Sans";
}
@media(max-width: 1200px) {
  .consulting-services-container {
    height: 672px;
  }
  .consulting-services-max-width {
    height: 658px;
  }
  .consulting-services-content {
    height: 653px;
    position: relative;
  }
  .consulting-services-ul {
    width: 1200px;
    height: 450px;
    position: relative;
  }
  .consulting-services-li {
    width: 1200px;
    height: 678px;
  }
  .consulting-services-heading1 {
    margin-left: 20px;
  }
  .consulting-services-content1 {
    margin-left: 40px;
    margin-bottom: var(--dl-space-space-doubleunit);
  }
  .consulting-services-ul1 {
    position: relative;
  }
  .consulting-services-content2 {
    margin-left: 20px;
    margin-right: 20px;
  }
  .consulting-services-ul2 {
    position: relative;
  }
  .consulting-services-content21 {
    margin-left: 20px;
    margin-right: 20px;
  }
  .consulting-services-ul3 {
    position: relative;
  }
  .consulting-services-content22 {
    margin-left: 20px;
    margin-right: 20px;
  }
  .consulting-services-ul4 {
    position: relative;
  }
  .consulting-services-content23 {
    margin-left: 20px;
    margin-right: 20px;
  }
}
@media(max-width: 990px) {
  .consulting-services-ul {
    width: 990px;
  }
  .consulting-services-li {
    width: 100%;
  }
}
@media(max-width: 767px) {
  .consulting-services-container {
    height: 722px;
    padding-bottom: 0px;
  }
  .consulting-services-max-width {
    height: 100%;
  }
  .consulting-services-content {
    height: 719px;
  }
  .consulting-services-ul {
    width: 767px;
    height: 100%;
  }
  .consulting-services-li {
    top: -2px;
    right: 5px;
    width: 767px;
    height: 722px;
    position: absolute;
  }
  .consulting-services-content1 {
    height: 80px;
    margin-left: 19px;
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .consulting-services-ul1 {
    height: 157px;
  }
  .consulting-services-content2 {
    font-family: Noto Sans;
  }
  .consulting-services-content21 {
    font-family: Noto Sans;
  }
}
@media(max-width: 479px) {
  .consulting-services-container {
    height: 1151px;
    margin-bottom: 4px;
  }
  .consulting-services-max-width {
    height: 100%;
  }
  .consulting-services-content {
    height: 1150px;
  }
  .consulting-services-ul {
    width: 479px;
    height: 100%;
  }
  .consulting-services-li {
    width: 479px;
    height: 1150px;
  }
  .consulting-services-content1 {
    height: 119px;
  }
  .consulting-services-ul1 {
    height: 265px;
  }
  .consulting-services-ul2 {
    height: 190px;
    padding-bottom: 0px;
  }
  .consulting-services-ul3 {
    height: 302px;
  }
}
</style>

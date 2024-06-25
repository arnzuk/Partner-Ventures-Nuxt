<template>
  <footer
    class="footer-container thq-section-padding"
    v-bind:class="rootClassName"
  >
    <div class="footer-max-width thq-section-max-width">
      <div class="footer-credits">
        <div class="footer-row">
          <div class="footer-credits1">
            <span class="thq-body-small">{{ privacyLink }}</span>
            <span class="thq-body-small">{{ termsLink }}</span>
            <span class="thq-body-small">{{ cookiesLink }}</span>
          </div>
        </div>
        <span class="footer-content3 thq-body-small">{{ copyright }}</span>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    cookiesLink: {
      type: String,
      default: 'Cookies Settings',
    },
    copyright: {
      type: String,
      default: '© 2024 MB Partner Ventures',
    },
    rootClassName: String,
    termsLink: {
      type: String,
      default: 'Terms of Service',
    },
    privacyLink: {
      type: String,
      default: 'Privacy Policy',
    },
  },
}
</script>

<style scoped>
.footer-container {
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.footer-max-width {
  display: flex;
  flex-direction: column;
}
.footer-credits {
  gap: 24px;
  width: auto;
  display: flex;
  align-self: stretch;
  align-items: stretch;
  flex-direction: column;
  justify-content: flex-start;
}
.footer-row {
  flex: 1;
  display: flex;
  align-self: center;
  align-items: flex-start;
  flex-shrink: 0;
  justify-content: space-between;
}
.footer-credits1 {
  gap: 32px;
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.footer-content3 {
  align-self: center;
}
.footer-root-class-name {
  left: 0px;
  bottom: 50px;
  position: absolute;
}
@media(max-width: 1200px) {
  .footer-container {
    height: 125px;
  }
  .footer-max-width {
    height: 74px;
  }
  .footer-credits {
    margin-top: 0px;
  }
  .footer-root-class-name {
    bottom: 0px;
  }
}
</style>

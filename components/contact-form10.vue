<template>
  <div
    class="contact-form10-contact11 thq-section-padding"
    v-bind:class="rootClassName"
  >
    <div class="contact-form10-max-width thq-section-max-width">
      <div class="contact-form10-section-title thq-card">
        <span class="thq-body-small">{{ content2 }}</span>
        <div class="contact-form10-content">
          <h2 class="contact-form10-text01 thq-heading-2">{{ contactTitle }}</h2>
          <p class="thq-body-large">{{ content1 }}</p>
        </div>
      </div>
      <div class="contact-form10-content1">
        <form class="contact-form10-form thq-card">
          <div class="contact-form10-input">
            <label for="contact-form-10-name" class="thq-body-small">Name</label>
            <input
              type="text"
              id="contact-form-10-name"
              placeholder="Full Name"
              class="contact-form10-text-input thq-input"
            />
          </div>
          <div class="contact-form10-input1">
            <label for="contact-form-10-email" class="thq-body-small">
              Email
            </label>
            <input
              type="text"
              id="contact-form-10-email"
              required="true"
              placeholder="Email"
              class="contact-form10-text-input1 thq-input"
            />
          </div>
          <div class="contact-form10-container">
            <div class="contact-form10-input2">
              <label for="contact-form-10-options" class="thq-body-small">
                Choose one topic
              </label>
              <select
                id="contact-form-10-options"
                placeholder="Select one"
                class="thq-select contact-form10-select"
              >
                <option value="Option 1">Feature request</option>
                <option value="Option 1">Customer Service</option>
              </select>
            </div>
          </div>
          <div class="contact-form10-input3">
            <label for="contact-form-10-message" class="thq-body-small">
              Message
            </label>
            <textarea
              id="contact-form-10-message"
              rows="3"
              placeholder="Enter your message"
              class="contact-form10-textarea thq-input"
            ></textarea>
          </div>
          <div class="contact-form10-checkbox">
            <input
              type="checkbox"
              id="contact-form-10-check"
              checked="true"
              required="true"
              class="thq-checkbox"
            />
            <label for="contact-form-10-check" class="thq-body-small">
              I accept the Terms
            </label>
          </div>
          <button type="submit" class="contact-form10-button thq-button-filled">
            <span class="thq-body-small">{{ submitAction }}</span>
          </button>
        </form>
        <div class="contact-form10-content2 thq-card">
          <div class="contact-form10-row thq-flex-row">
            <div class="contact-form10-content3">
              <svg
                viewBox="0 0 1024 1024"
                class="contact-form10-icon thq-icon-small"
              >
                <path
                  d="M854 342v-86l-342 214-342-214v86l342 212zM854 170q34 0 59 26t25 60v512q0 34-25 60t-59 26h-684q-34 0-59-26t-25-60v-512q0-34 25-60t59-26h684z"
                ></path>
              </svg>
              <div class="contact-form10-contact-info">
                <h3 class="contact-form10-text08 thq-heading-3">Email</h3>
                <span class="thq-body-small">{{ email }}</span>
              </div>
            </div>
            <div class="contact-form10-content4">
              <svg
                viewBox="0 0 1024 1024"
                class="contact-form10-icon2 thq-icon-small"
              >
                <path
                  d="M282 460q96 186 282 282l94-94q20-20 44-10 72 24 152 24 18 0 30 12t12 30v150q0 18-12 30t-30 12q-300 0-513-213t-213-513q0-18 12-30t30-12h150q18 0 30 12t12 30q0 80 24 152 8 26-10 44z"
                ></path>
              </svg>
              <div class="contact-form10-contact-info1">
                <h3 class="contact-form10-text09 thq-heading-3">Phone</h3>
                <span class="thq-body-small">{{ phone }}</span>
              </div>
            </div>
            <div class="contact-form10-content5">
              <svg
                viewBox="0 0 1024 1024"
                class="contact-form10-icon4 thq-icon-small"
              >
                <path
                  d="M512 0c-176.732 0-320 143.268-320 320 0 320 320 704 320 704s320-384 320-704c0-176.732-143.27-320-320-320zM512 512c-106.040 0-192-85.96-192-192s85.96-192 192-192 192 85.96 192 192-85.96 192-192 192z"
                ></path>
              </svg>
              <div class="contact-form10-contact-info2">
                <h3 class="contact-form10-text10 thq-heading-3">Office</h3>
                <span class="thq-body-small">{{ address }}</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactForm10',
  props: {
    submitAction: {
      type: String,
      default: 'Send Message',
    },
    contactTitle: {
      type: String,
      default: 'Contact Us',
    },
    content2: {
      type: String,
      default: 'We are here to assist you with any inquiries you may have.',
    },
    phone: {
      type: String,
      default: '+370 12345678',
    },
    address: {
      type: String,
      default: 'Partner Ventures, Vilnius, Lithuania',
    },
    email: {
      type: String,
      default: 'info@partnerventures.com',
    },
    rootClassName: String,
    content1: {
      type: String,
      default:
        'Have a question or need more information? Feel free to reach out to us.',
    },
  },
}
</script>

<style scoped>
.contact-form10-contact11 {
  gap: 48px;
  display: flex;
  overflow: hidden;
  position: relative;
  flex-direction: column;
}
.contact-form10-max-width {
  height: 872px;
  display: flex;
  position: relative;
  flex-direction: column;
}
.contact-form10-section-title {
  gap: var(--dl-space-space-unit);
  top: 16px;
  left: 688px;
  width: 816px;
  display: flex;
  position: absolute;
  flex-direction: column;
}
.contact-form10-content {
  gap: 24px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-text01 {
  font-family: "Noto Sans";
}
.contact-form10-content1 {
  display: flex;
  position: relative;
  align-self: stretch;
  align-items: flex-start;
}
.contact-form10-form {
  gap: 24px;
  top: 178px;
  flex: 1;
  left: 448px;
  width: 1065px;
  display: flex;
  position: absolute;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.contact-form10-input {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-text-input {
  font-family: "Noto Sans";
}
.contact-form10-input1 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-text-input1 {
  font-family: "Noto Sans";
  background-color: var(--dl-color-theme-neutral-light);
}
.contact-form10-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-input2 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-input3 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-textarea {
  font-family: "Noto Sans";
}
.contact-form10-checkbox {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
}
.contact-form10-button {
  background-color: #058512;
}
.contact-form10-content2 {
  left: 135px;
  bottom: -217px;
  position: absolute;
  align-items: stretch;
}
.contact-form10-row {
  top: -83px;
  right: -2200px;
  width: 568px;
  height: 547px;
  position: absolute;
  align-items: flex-start;
}
.contact-form10-icon {
  width: 32px;
  height: 32px;
}
.contact-form10-contact-info {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-text08 {
  font-family: "Noto Sans";
}
.contact-form10-content4 {
  top: 207px;
  left: 0px;
  position: absolute;
}
.contact-form10-icon2 {
  width: 32px;
  height: 32px;
}
.contact-form10-contact-info1 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-text09 {
  font-family: "Noto Sans";
}
.contact-form10-content5 {
  left: 0px;
  bottom: 23px;
  position: absolute;
}
.contact-form10-icon4 {
  width: 32px;
  height: 32px;
}
.contact-form10-contact-info2 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.contact-form10-text10 {
  font-family: "Noto Sans";
}
.contact-form10-root-class-name {
  top: -166px;
  right: -10px;
  position: absolute;
}
@media(max-width: 1920px) {
  .contact-form10-form {
    top: 199px;
    left: 143px;
  }
  .contact-form10-row {
    top: -28px;
    right: -1720px;
    width: 459px;
  }
}
@media(max-width: 1200px) {
  .contact-form10-contact11 {
    height: 1223px;
  }
  .contact-form10-max-width {
    height: 100%;
  }
  .contact-form10-section-title {
    top: 35px;
    left: 131px;
    width: 489px;
    position: absolute;
  }
  .contact-form10-form {
    top: 233px;
    left: 76px;
  }
  .contact-form10-select {
    width: 180px;
  }
  .contact-form10-content2 {
    left: 119px;
    bottom: -759px;
  }
  .contact-form10-row {
    top: 22px;
    left: 103px;
    width: 831px;
    height: 206px;
    position: absolute;
  }
  .contact-form10-content3 {
    top: 4px;
    left: 82px;
    width: 180px;
    height: 141px;
    margin: auto;
    position: absolute;
  }
  .contact-form10-icon {
    top: 2px;
    left: 78px;
    margin: auto;
    position: absolute;
  }
  .contact-form10-contact-info {
    width: 163px;
    height: 113px;
  }
  .contact-form10-content4 {
    top: 7px;
    left: 302px;
  }
  .contact-form10-icon2 {
    top: 0px;
    right: -1px;
    position: absolute;
  }
  .contact-form10-content5 {
    top: 0px;
    left: 500px;
    right: 90px;
    width: 218px;
    height: 129px;
    position: absolute;
  }
  .contact-form10-icon4 {
    top: 0px;
    left: 81px;
    position: absolute;
  }
}
@media(max-width: 991px) {
  .contact-form10-form {
    width: 50%;
  }
  .contact-form10-container {
    gap: 32px;
    width: 100%;
    flex-direction: row;
  }
  .contact-form10-input2 {
    gap: var(--dl-space-space-halfunit);
    width: 100%;
    flex-direction: column;
  }
  .contact-form10-content2 {
    width: 50%;
  }
  .contact-form10-row {
    flex-direction: column;
  }
  .contact-form10-content3 {
    width: 50%;
  }
  .contact-form10-contact-info {
    width: 50%;
  }
  .contact-form10-content4 {
    width: 50%;
  }
}
@media(max-width: 990px) {
  .contact-form10-form {
    width: 882px;
  }
  .contact-form10-content2 {
    left: 24px;
    bottom: -763px;
  }
}
@media(max-width: 767px) {
  .contact-form10-form {
    width: 634px;
  }
  .contact-form10-input2 {
    width: 100%;
  }
  .contact-form10-content2 {
    left: -81px;
    bottom: -755px;
  }
}
@media(max-width: 479px) {
  .contact-form10-contact11 {
    height: 1375px;
  }
  .contact-form10-section-title {
    width: 315px;
    margin-right: 0px;
  }
  .contact-form10-content1 {
    flex-direction: column;
  }
  .contact-form10-form {
    top: 262px;
    left: 70px;
    width: 357px;
  }
  .contact-form10-input2 {
    width: 100%;
  }
  .contact-form10-content2 {
    left: -113px;
    width: 100%;
    bottom: -796px;
  }
  .contact-form10-row {
    width: 478px;
    height: 487px;
    flex-direction: column;
    padding-bottom: 0px;
  }
  .contact-form10-content3 {
    width: 290px;
    height: 98px;
  }
  .contact-form10-content4 {
    top: 152px;
    left: 84px;
    width: 191px;
  }
  .contact-form10-icon2 {
    top: 7px;
    left: 90px;
  }
  .contact-form10-content5 {
    top: 264px;
    left: 85px;
    width: 192px;
    height: 95px;
  }
}
</style>

<template>
  <footer id="contacts" class="scrollspy">
    <div class="row">
      <div class="container">
        <div class="footer-contents-wrapper">
          <div class="footer-content-block footer-logo-block">
            <img src="~/assets/images/arila-white.svg" alt="Arila" class="footer-logo">

            <div class="inq tel-inq">
              <ul>
                <li>
                  <img src="~/assets/images/call.svg" alt="call">
                  <a href="tel:+2347034145958">+234 703 4145 958</a>
                </li>
                <li>
                  <img src="~/assets/images/mail.svg" alt="email">
                  <a href="mailto:contact@arila.org">contact@arila.org</a>
                </li>
              </ul>
            </div>
          </div>

          <div class="footer-content-block">
            <div class="footer-sec-title">
              General inquiries
            </div>
            <div class="footer-sec-content">
              <ul class="footer-links-wrapper">
                <li>
                  <nuxt-link to="/" class="footer-link">
                    Home
                  </nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/approach" class="footer-link">
                    Our Approach
                  </nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/leadership" class="footer-link">
                    Leadership
                  </nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/join-us" class="footer-link">
                    Join Us
                  </nuxt-link>
                </li>
                <!-- <li>
                  <nuxt-link to="/contact" class="footer-link">
                    Contact us
                  </nuxt-link>
                </li> -->
              </ul>
            </div>
          </div>

          <div class="footer-content-block">
            <div class="footer-sec-title">
              Our Social Media
            </div>
            <div class="footer-sec-content">
              <div class="footer-social-wrapper">
                <a href="http://facebook.com" target="_blank" rel="noopener noreferrer">
                  <img src="~/assets/images/facebook.svg" alt="facebook" class="social-icons">
                </a>

                <a href="http://twitter.com" target="_blank" rel="noopener noreferrer">
                  <img src="~/assets/images/twitter.svg" alt="twitter" class="social-icons">
                </a>
                <a href="http://whatsapp.com" target="_blank" rel="noopener noreferrer">
                  <img src="~/assets/images/whatsapp.svg" alt="whatsapp" class="social-icons">
                </a>
                <a href="http://linkedin.com" target="_blank" rel="noopener noreferrer">
                  <img src="~/assets/images/linkedin.svg" alt="linkedin" class="social-icons">
                </a>
              </div>
            </div>
          </div>

          <div id="mc_embed_signup" class="footer-content-block">
            <div class="footer-sec-title">
              Join Our Newsletter
            </div>
            <div class="footer-sec-content">
              <div class="subscribe-form-wrapper">
                <form
                  id="mc-embedded-subscribe-form"
                  action="https://arila.us10.list-manage.com/subscribe/post?u=4fc563423b0235bb20d536ed0&amp;id=5466ed2088&amp;f_id=002ac6e5f0"
                  method="post"
                  name="mc-embedded-subscribe-form"
                  class="validate"
                  target="_blank"
                  novalidate
                >
                  <div class="flex-div input-field">
                    <label for="mce-EMAIL" class="active">Your Email</label>
                    <input
                      id="mce-EMAIL"
                      class="required email"
                      name="EMAIL"
                      placeholder="Enter Your Email"
                      type="email"
                      required
                    >
                    <span id="mce-EMAIL-HELPERTEXT" class="helper_text" />

                    <div id="mce-responses" class="clear foot">
                      <div id="mce-error-response" class="response" style="display: none;" />
                      <div id="mce-success-response" class="response" style="display: none;" />
                    </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
                    <div style="position: absolute; left: -5000px;" aria-hidden="true">
                      <input type="text" name="b_4fc563423b0235bb20d536ed0_5466ed2088" tabindex="-1" value="">
                    </div>

                    <button id="mc-embedded-subscribe" class="btn subscribe-submit sec-bg" name="subscribe">
                      Subscribe
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-credit-wrapper">
        <div class="row">
          <div class="container">
            <div class="footer-sub-wrapper">
              <div>© 2022 Arila Business Management.</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import $ from 'jquery'
export default {
  name: 'FooterComp',
  mounted () {
    $('#mc-embedded-subscribe').click(function () {
      $('#mce-EMAIL').val('')
    })
  }
}
</script>

<style scoped src="..\assets\css\footer.css"></style>

<template>
  <div id="nav-wrapper">
    <!---=== Add .nav-2 to give it a white-background mode ===--->
    <nav class="main-nav">
      <div class="container full-height">
        <div class="nav-wrapper">
          <nuxt-link to="/" class="brand-logo" @click="scrollToTop()">
            <img src="~/assets/images/arila-white.svg" alt="Arila" class="logo white-img">
            <img src="~/assets/images/arila.svg" alt="Arila" class="logo colored-img">
          </nuxt-link>

          <ul id="nav-mobile-2" class="dn-mobile ul-nav">
            <li>
              <a href="#" data-target="slide-out" class="sidenav-trigger sec-color right">
                <img src="~/assets/images/menu.svg" alt="menu" class="white-img">
                <img src="~/assets/images/menu-blue.svg" alt="menu" class="colored-img">
              </a>
            </li>
          </ul>

          <ul id="nav-mobile" class="right hide-on-med-and-down">
            <li>
              <nuxt-link to="/approach" @click="scrollToTop()">
                <span>Our Approach</span>
              </nuxt-link>
            </li>
            <li>
              <nuxt-link to="/leadership" @click="scrollToTop()">
                <span>Leadership</span>
              </nuxt-link>
            </li>
            <li>
              <nuxt-link to="/join-us" @click="scrollToTop()">
                <span>Partners & Stakeholders</span>
              </nuxt-link>
            </li>
            <!-- <li>
              <nuxt-link to="/join-us" class="nav-pry-btn btn" @click="scrollToTop()">
                Join Us
              </nuxt-link>
            </li> -->
          </ul>
        </div>
      </div>
    </nav>

    <ul id="slide-out" class="sidenav">
      <div class="sidenav-logo">
        <nuxt-link to="/" class="sidenav-close" @click="scrollToTop()">
          <img src="~/assets/images/arila.svg" alt="Arila" class="logo">
        </nuxt-link>
      </div>
      <ul class="sidenav-flex">
        <!-- <li>
          <nuxt-link to="/" class="sidenav-close" @click="scrollToTop()">
            <span>Home</span>
          </nuxt-link>
        </li> -->
        <li>
          <nuxt-link to="/approach" class="sidenav-close" @click="scrollToTop()">
            <span>Our Approach</span>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/leadership" class="sidenav-close" @click="scrollToTop()">
            <span>Leadership</span>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/join-us" class="sidenav-close" @click="scrollToTop()">
            <span>Partners & Stakeholders</span>
          </nuxt-link>
        </li>
        <!-- <li>
          <nuxt-link to="/join-us" class="sidenav-close">
            <button class="nav-pry-btn btn pointer">
              Join Us
            </button>
          </nuxt-link>
        </li> -->
      </ul>
      <div class="sidenav-footer">
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
    </ul>
  </div>
</template>

<script>
// import M from 'materialize-css'
// import $ from "jquery";
export default {
  name: 'NavbarComp',
  mounted () {
    const M = require('materialize-css')

    const elemsSidenav = document.querySelectorAll('.sidenav')
    M.Sidenav.init(elemsSidenav)
    const elemsScrollspy = document.querySelectorAll('.scrollspy')
    M.ScrollSpy.init(elemsScrollspy)
  },
  methods: {
    scrollToTop () {
      window.scrollTo(0, 0)
    }
  }
}
</script>

<style scoped src="..\assets\css\navbar.css"></style>

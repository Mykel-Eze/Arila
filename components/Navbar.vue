<template>
  <div>
    <nav class="main-nav">
      <div class="container">
        <div class="nav-wrapper">
          <nuxt-link to="/" class="brand-logo" @click="scrollToTop()">
            <img src="~/assets/images/arila.svg" alt="Arila" class="logo">
          </nuxt-link>

          <ul id="nav-mobile-2" class="dn-mobile ul-nav">
            <li>
              <a href="#" data-target="slide-out" class="sidenav-trigger sec-color right">
                <img src="~/assets/images/menu.svg" alt="menu">
              </a>
            </li>
          </ul>

          <ul id="nav-mobile" class="right hide-on-med-and-down">
            <li>
              <a href="#ethos" class="">
                <span>Our Ethos</span>
              </a>
            </li>
            <li>
              <a href="#about-arila" class="">
                <span>About Arila</span>
              </a>
            </li>
            <li>
              <a href="#objectives" class="">
                <span>Objectives</span>
              </a>
            </li>
            <li>
              <a href="#our-impact" class="">
                <span>Impact</span>
              </a>
            </li>
            <li>
              <a href="#our-legacy" class="">
                <span>Legacy</span>
              </a>
            </li>
            <li>
              <a href="#contacts" class="">
                <button class="nav-pry-btn btn pointer">Contact Us</button>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <ul id="slide-out" class="sidenav">
      <div class="sidenav-logo">
        <nuxt-link to="/" class="sidenav-close" @click="scrollToTop()">
          <img src="~/assets/images/arila-white.svg" alt="Arila" class="logo">
        </nuxt-link>
      </div>
      <li>
        <a href="#home" class="sidenav-close">
          <span>Home</span>
        </a>
      </li>
      <li>
        <a href="#ethos" class="sidenav-close">
          <span>Our Ethos</span>
        </a>
      </li>
      <li>
        <a href="#about-arila" class="sidenav-close">
          <span>About Arila</span>
        </a>
      </li>
      <li>
        <a href="#objectives" class="sidenav-close">
          <span>Objectives</span>
        </a>
      </li>
      <li>
        <a href="#our-impact" class="sidenav-close">
          <span>Impact</span>
        </a>
      </li>
      <li>
        <a href="#our-legacy" class="sidenav-close">
          <span>Legacy</span>
        </a>
      </li>
      <li>
        <a href="#contacts" class="sidenav-close">
          <button class="nav-pry-btn btn pointer">Contact Us</button>
        </a>
      </li>
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

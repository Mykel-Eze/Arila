<template>
  <section id="home" data-slide="1" class="scrollspy">
    <div class="row full-height rel">
      <div class="container full-height">
        <div class="carousel carousel-slider full-height">
          <div class="carousel-fixed-item slider-number-wrapper">
            <div class="current-slide-number">
              01
            </div>
            <div class="slider-numbers flex-div">
              <span id="current-num">01</span>
              <div class="progress">
                <div class="determinate" style="width: 25%;" />
              </div>
              <span>04</span>
            </div>
          </div>

          <div class="carousel-fixed-item flex-div justify-content-btw">
            <div class="slider-navigations flex-div">
              <img id="prev-slide" src="~/assets/images/prev-slide.svg" alt="previous" @click="prev()">
              <img id="next-slide" src="~/assets/images/next-slide.svg" alt="next" @click="next()">
            </div>
            <div class="home-social-links flex-div">
              <a href="https://facebook.com" target="_blank" rel="noopener noreferrer">
                <img src="~/assets/images/facebook-white.svg" alt="facebook">
              </a>
              <a href="https://twitter.com" target="_blank" rel="noopener noreferrer">
                <img src="~/assets/images/twitter-white.svg" alt="twitter">
              </a>
              <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer">
                <img src="~/assets/images/linkedin-white.svg" alt="linkedin">
              </a>
            </div>
          </div>

          <div id="home-slide-1" class="carousel-item" href="#one!">
            <div class="container full-height">
              <div class="home-txt-wrapper">
                <h1 class="home-txt-title">
                  Building the flow of food, finance, energy & transport <span class="sec-color">across Africa.</span>
                </h1>
                <div class="home-txt-desc">
                  Join us to provide access at scale to affordable food, clean energy,
                  low-cost finance and efficient connectivity
                </div>
                <div class="home-btn-wrapper">
                  <nuxt-link to="/join-us" class="home-btn btn">
                    Join Us
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div id="home-slide-2" class="carousel-item" href="#two!">
            <div class="container full-height">
              <div class="home-txt-wrapper">
                <h1 class="home-txt-title">
                  Building the flow of food, finance, energy & transport <span class="sec-color">across Africa.</span>
                </h1>
                <div class="home-txt-desc">
                  Join us to provide access at scale to affordable food, clean energy,
                  low-cost finance and efficient connectivity
                </div>
                <div class="home-btn-wrapper">
                  <nuxt-link to="/join-us" class="home-btn btn">
                    Join Us
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div id="home-slide-3" class="carousel-item" href="#three!">
            <div class="container full-height">
              <div class="home-txt-wrapper">
                <h1 class="home-txt-title">
                  Building the flow of food, finance, energy & transport <span class="sec-color">across Africa.</span>
                </h1>
                <div class="home-txt-desc">
                  Join us to provide access at scale to affordable food, clean energy,
                  low-cost finance and efficient connectivity
                </div>
                <div class="home-btn-wrapper">
                  <nuxt-link to="/join-us" class="home-btn btn">
                    Join Us
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div id="home-slide-4" class="carousel-item" href="#four!">
            <div class="container full-height">
              <div class="home-txt-wrapper">
                <h1 class="home-txt-title">
                  Building the flow of food, finance, energy & transport <span class="sec-color">across Africa.</span>
                </h1>
                <div class="home-txt-desc">
                  Join us to provide access at scale to affordable food, clean energy,
                  low-cost finance and efficient connectivity
                </div>
                <div class="home-btn-wrapper">
                  <nuxt-link to="/join-us" class="home-btn btn">
                    Join Us
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <a href="#solar-pump" class="hover-scroll-btn">
        <img src="~/assets/images/scroll-button.svg" alt="scroll">
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HomeSection',
  data () {
    return {
      currentSlide: 1
    }
  },
  mounted () {
    const $ = require('jquery')
    const M = require('materialize-css')

    const elemsCarousel1 = document.querySelectorAll('#home .carousel')
    M.Carousel.init(elemsCarousel1, {
      fullWidth: true,
      onCycleTo (data) {
        const currentSlide = $(data).index() + 1
        const currentSlideNum = currentSlide - 2
        document.querySelector('.current-slide-number').innerHTML = '0' + currentSlideNum
        document.querySelector('#current-num').innerHTML = '0' + currentSlideNum

        document.querySelector('#home').setAttribute('data-slide', currentSlideNum)
        document.querySelector('#home .progress .determinate').style.width = (currentSlideNum * 25) + 'px'
      }
    })

    autoplay()
    function autoplay () {
      const elemSlide = document.querySelector('#home .carousel')
      M.Carousel.getInstance(elemSlide).next()

      setTimeout(autoplay, 4000)
    }
    setTimeout(autoplay, 4000)
  },
  methods: {
    prev () {
      const M = require('materialize-css')
      const elemSlide = document.querySelector('#home .carousel')
      M.Carousel.getInstance(elemSlide).prev()
    },
    next () {
      const M = require('materialize-css')
      const elemSlide = document.querySelector('#home .carousel')
      M.Carousel.getInstance(elemSlide).next()
    }
  }
}
</script>

<style scoped>
  #home[data-slide="1"] {
    background-image: url("~/assets/images/hero-1a.jpg");
  }

  #home[data-slide="2"] {
    background-image: url("~/assets/images/hero-3.jpg");
  }

  #home[data-slide="3"] {
    background-image: url("~/assets/images/hero-2a.jpg");
  }

  #home[data-slide="4"] {
    background-image: url("~/assets/images/hero-4a.jpg");
  }
</style>

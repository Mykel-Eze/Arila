<template>
  <div id="leadership-details-page">
    <!---=== Home Section ===--->
    <section id="leader-details-home" class="rel">
      <div class="ldh flex-div">
        <div class="ldh-img-side">
          <img src="~/assets/images/leadership/dr-debisi-araba-2.jpg" alt="Dr. Debisi Araba" class="ldh-img">
        </div>
        <div class="ldh-txt-side rel">
          <div class="ldh-txt-holder">
            <div class="board-role-txt sec-color">
              ADVISORY BOARD
            </div>
            <h2 class="section-title">
              Dr. Debisi<br class="hidden-xs-sm"> Araba
            </h2>
            <p class="board-member-desc">
              Dr. Debisi Araba is a public policy, innovation and strategy specialist focused on the future of
              food, the environment, and entrepreneurship.
            </p>
          </div>
          <img src="~/assets/images/mask-m.svg" alt="vector" class="mask-m">
        </div>
      </div>
      <a href="#top-biography" class="hover-scroll-btn">
        <img src="~/assets/images/scroll-button.svg" alt="scroll">
      </a>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== Top-Biography Section ===--->
    <section id="top-biography">
      <div class="row">
        <div class="container">
          <div class="tb-grid-wrapper">
            <div class="tb-bold-txt bold-txt">
              He is currently a Visiting Research Fellow at the Centre for Environmental Policy, Imperial College London.
            </div>
            <div class="tb-normal-txt">
              He also serves on the Montpellier Malabo Panel of experts – an eminent group of global experts – working
              together to enhance African and European government support of national and regional agricultural development
              and food security priorities in Africa.
            </div>
          </div>
        </div>

        <div class="biography-divider">
          <div class="container">
            <hr class="bd-hr">
          </div>
        </div>

        <div class="more-biography-detials">
          <div class="container">
            <p>
              Previously, he led the Africa Green Revolution Forum (AGRF) as the Managing Director, and was also the Africa
              Region Director at the International Center for Tropical Agriculture (CIAT), a member of the CGIAR, the
              consortium on international agriculture research.
            </p>
            <p>
              He has also served as the Senior Technical Adviser on Environmental Policy to the Minister of Agriculture and
              Rural Development in Nigeria. Debisi has a Doctorate degree from the Centre for Environmental Policy, Imperial
              College London, a Masters in Public Administration from the Harvard University Kennedy School of Government,
              a Masters in Clean Technology from the University of Newcastle Upon Tyne and a Bachelors degree in Physical
              Geography from the University of Ibadan.
            </p>
          </div>
        </div>

        <div class="back-to-team">
          <nuxt-link to="/leadership" class="flex-div">
            <img src="~/assets/images/left-arr-green.svg" alt="left arrow" class="left-arr">
            <span>Back to Team</span>
          </nuxt-link>
        </div>
      </div>
    </section>
    <!---=== end of Top-Biography Section ===--->
  </div>
</template>

<script>
export default {
  name: 'DrDebisiAraba'
}
</script>

<style src="../../assets/css/leadership.css"></style>

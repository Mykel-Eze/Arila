<template>
  <div id="leadership-details-page">
    <!---=== Home Section ===--->
    <section id="leader-details-home" class="rel">
      <div class="ldh flex-div">
        <div class="ldh-img-side">
          <img src="~/assets/images/leadership/dimieari-von-kemedi-2.jpg" alt="Dimieari Von Kemedi" class="ldh-img">
        </div>
        <div class="ldh-txt-side rel">
          <div class="ldh-txt-holder">
            <div class="board-role-txt sec-color">
              ADVISORY BOARD
            </div>
            <h2 class="section-title">
              Dimieari Von <br class="hidden-xs-sm"> Kemedi
            </h2>
            <p class="board-member-desc">
              Dimieari Von Kemedi is the Managing Director of Arila Business Management, which provides group
              management to several operating companies focused on the important challenges confronting Africa.
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
              He is promoting large scale integrated initiatives in agriculture, food and retail, fintech, logistics
              and renewable energy.
            </div>
            <div class="tb-normal-txt">
              He has an intimate understanding of the business solutions required to drive progress and combines this
              with extensive networks in key sectors of the African economy and society.
            </div>
          </div>
        </div>

        <div class="biography-pictures">
          <div>
            <img src="~/assets/images/leadership/von-1.jpg" alt="Dimieari Von Kemedi">
          </div>
          <div>
            <img src="~/assets/images/leadership/von-2.jpg" alt="Dimieari Von Kemedi">
          </div>
          <div>
            <img src="~/assets/images/leadership/von-3.jpg" alt="Dimieari Von Kemedi">
          </div>
        </div>

        <div class="more-biography-detials">
          <div class="container">
            <p>
              Together with a high level international advisory council, strong governance systems, and a team of
              talented planners and capable executors, Kemedi is deploying these strengths to a series of bold
              initiatives that present unique opportunities for governments, financiers, smallholder farmers, SMEs,
              equipment manufacturers and investors to meet their objectives at a scale that matches the opportunities
              or problems at hand.
            </p>
            <p>
              Kemedi has served in a number of senior expert positions including with the United Nations Development
              Program (UNDP) and the UN Panel of Experts on Liberia. He holds a law degree from the Rivers State University
              of Science & Technology, Port Harcourt, and has studied as an Environmental Politics Visiting Fellow at the
              University of California, Berkeley.
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
  name: 'DimieariVonKemedi'
}
</script>

<style src="../../assets/css/leadership.css"></style>

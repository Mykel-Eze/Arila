<template>
  <div id="leadership-details-page">
    <!---=== Home Section ===--->
    <section id="leader-details-home" class="rel">
      <div class="ldh flex-div">
        <div class="ldh-img-side">
          <img src="~/assets/images/leadership/bishop-precious-omuku-2.jpg" alt="Bishop Precious Omuku" class="ldh-img">
        </div>
        <div class="ldh-txt-side rel">
          <div class="ldh-txt-holder">
            <div class="board-role-txt sec-color">
              ADVISORY BOARD
            </div>
            <h2 class="section-title">
              Bishop Precious<br class="hidden-xs-sm"> Omuku
            </h2>
            <p class="board-member-desc">
              Bishop Precious Omuku is the Chairman of Arila Group.
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
              He has served as a member of the governing council of Ahmadu Bello University, Zaria.
            </div>
            <div class="tb-normal-txt">
              A professional geologist, Omuku held senior positions in Shell Nigeria and Shell UK before his
              appointment as Shell Nigeria's chief geologist, and later, Executive Director External Affairs,
              Director of Shell Trustees Ltd., Chairman, Board of Shell Nigeria Gas, and Senior Advisor, Shell
              International, London - a position he held until he retired from Shell.
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
              He has served as a member of the governing council of Ahmadu Bello University, Zaria, a member of the
              board of the Nigerian Mining Corporation, chairman of the Rivers State of Nigeria Bureau of Public Procurement,
              chairman of the Rivers State (of Nigeria) Sustainable Development Agency, and Archbishop of Canterbury's
              Adviser on Anglican Communion Affairs.
            </p>
            <p>
              Omuku is a member of the Board of Trustees of the Rivers Community Development Foundation (set up by the World Bank),
              member of Friends Life Committee of Reference, a Bishop of South Sudan and Sudan, an Assistant Bishop in the
              Diocese of Southwark, Church of England, and an Assistant to the Archbishop of Canterbury.
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
  name: 'BishopPreciousOmuku'
}
</script>

<style src="../../assets/css/leadership.css"></style>

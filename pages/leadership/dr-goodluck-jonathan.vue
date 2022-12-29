<template>
  <div id="leadership-details-page">
    <!---=== Home Section ===--->
    <section id="leader-details-home" class="rel">
      <div class="ldh flex-div">
        <div class="ldh-img-side">
          <img src="~/assets/images/leadership/goodluck-ebele-jonathan-2.jpg" alt="Dr. Goodluck Ebele Jonathan" class="ldh-img">
        </div>
        <div class="ldh-txt-side rel">
          <div class="ldh-txt-holder">
            <div class="board-role-txt sec-color">
              ADVISORY BOARD
            </div>
            <h2 class="section-title">
              Dr. Goodluck <br class="hidden-xs-sm"> Ebele Jonathan
            </h2>
            <p class="board-member-desc">
              Dr. Goodluck Ebele Azikiwe Jonathan GCFR, GCON is the Chairman, Advisory Board, Arila Business Management.
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
              Served as the President of Nigeria from 2010 - 2015.
            </div>
            <div class="tb-normal-txt">
              Born November 20, 1957, Dr. Jonathan served as the President of Nigeria from 2010 to 2015. He was the first
              incumbent president in Nigerian history to concede defeat in an election after losing the 2015
              presidential election. Before that, he served as Vice President of Nigeria from 2007 to 2010 under
              the administration of Umaru Musa Yar'Adua; and in the oil-rich Bayelsa State as Governor of Bayelsa State
              from 2005 to 2007.
            </div>
          </div>
        </div>

        <div class="biography-pictures">
          <div>
            <img src="~/assets/images/leadership/jonathan-1.jpg" alt="Dr. Goodluck Ebele Jonathan in an ECOWAS meeting">
          </div>
          <div>
            <img src="~/assets/images/leadership/jonathan-2.jpg" alt="Dr. Goodluck Ebele shaking hands with Barack Obama">
          </div>
          <div>
            <img src="~/assets/images/leadership/jonathan-3.jpg" alt="Dr. Goodluck Ebele Jonathan with Akinwunmi Adeshina">
          </div>
        </div>

        <div class="more-biography-detials">
          <div class="container">
            <p>
              Under Jonathan's administration, Nigeria rebased its gross domestic product for the first time in
              over a decade, becoming the largest economy in Africa by overtaking South Africa and Egypt. The
              Jonathan-led administration accrued over US$454 billion while in office from oil revenue. Jonathan
              previously served as an assistant director at the Oil Mineral Producing Areas Development Commission
              between 1993 and 1998. On 2 August 2010, Jonathan launched his 'Roadmap for Power Sector Reform'.
              Its primary goal was to achieve stable electricity supply in Nigeria.
            </p>
            <p>
              During Jonathan's administration, Nigeria's foreign policy was reviewed to reflect a "citizen-focused"
              approach, designed to "accord this vision of defending the dignity of humanity the highest priority"
              and connect foreign policy to domestic policy, while placing a greater emphasis on economic diplomacy.
            </p>
            <p>
              In June 2019, Goodluck Jonathan was named chairperson of the International Summit Council for Peace.
              In July 2020, he was appointed special envoy of the Economic Community of West African States (ECOWAS);
              to lead mediation talks during the 2020 Malian protests.
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
  name: 'GoodluckEbeleJonathan'
}
</script>

<style src="../../assets/css/leadership.css"></style>

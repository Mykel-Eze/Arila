<template>
  <div id="leadership-details-page">
    <!---=== Home Section ===--->
    <section id="leader-details-home" class="rel">
      <div class="ldh flex-div">
        <div class="ldh-img-side">
          <img src="~/assets/images/leadership/colonel-hamish-macdonald-2.jpg" alt="Colonel Hamish Macdonald" class="ldh-img">
        </div>
        <div class="ldh-txt-side rel">
          <div class="ldh-txt-holder">
            <div class="board-role-txt sec-color">
              ADVISORY BOARD
            </div>
            <h2 class="section-title">
              Colonel Hamish<br class="hidden-xs-sm"> Macdonald
            </h2>
            <p class="board-member-desc">
              Colonel Hamish Macdonald, who is a member of Arila’s Advisory Board, has had a vibrant career that
              spans both the military and commercial sectors.
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
              He served on operations globally with the UK Armed Forces and the UN including the 1991 Gulf War.
            </div>
            <div class="tb-normal-txt">
              He also commanded a multi-national battlegroup in the 1996 NATO invention in Bosnia. He was also
              one of the authors that wrote the new leadership approach which drives the current UK command philosophy.
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
              In 2002, he started his own consultancy supporting global oil and gas companies with focus on challenging
              operating environments including Africa and Asia using digitisation to improve performance, governance
              and transparency. The digitised system was also recognised in the conservation sector as a winner in the
              2016 Wildlife Crime Technology Challenge.
            </p>
            <p>
              He now lives and farms in Gloucestershire, UK.
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
  name: 'ColonelHamishMacdonald'
}
</script>

<style src="../../assets/css/leadership.css"></style>

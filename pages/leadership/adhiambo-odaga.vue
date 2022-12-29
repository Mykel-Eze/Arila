<template>
  <div id="leadership-details-page">
    <!---=== Home Section ===--->
    <section id="leader-details-home" class="rel">
      <div class="ldh flex-div">
        <div class="ldh-img-side">
          <img src="~/assets/images/leadership/adhiambo-odaga-2.jpg" alt="Dr. Adhiambo Odaga" class="ldh-img">
        </div>
        <div class="ldh-txt-side rel">
          <div class="ldh-txt-holder">
            <div class="board-role-txt sec-color">
              ADVISORY BOARD
            </div>
            <h2 class="section-title">
              Dr. Adhiambo<br class="hidden-xs-sm"> Odaga
            </h2>
            <p class="board-member-desc">
              Dr Adhiambo Odaga is a member of Arila’s Advisory Board.
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
              In 2004, her innovative and impactful leadership in development earned her a national honor from the then
              Nigerian President Olusegun Obasanjo government.
            </div>
            <div class="tb-normal-txt">
              She is also an independent executive consultant providing strategic organizational guidance to private,
              public and civic organizations with a view to improving profitability and social impact. Prior to this,
              as the pioneer Managing Director of the Dangote Foundation, a leading corporate foundation promoting health,
              and empowerment and supporting humanitarian work in Nigeria and around the world, she established governance,
              programme and operational systems; managed annual grantmaking of over $150 million in health, nutrition,
              economic empowerment education and construction.
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
              She also oversaw the establishment of Dangote Group's Environment, Health, Safety and Social Directorate
              to standardize its sustainability practices across all its business units.
            </p>
            <p>
              As Ford Foundation’s Director of Pan Africa Programs/Representative-West Africa she oversaw and funded
              programs that promoted rule of law, human rights and good governance, advocated for improved reproductive
              health for youth and women, advanced economic development, culture, and philanthropy and championed media
              pluralism. In 2004, her innovative and impactful leadership in development earned her a national honor from
              the then Nigerian President Olusegun Obasanjo government.
            </p>
            <p>
              Prior to that, at the WorldBank she worked on girls’ education in Africa. And as a Rockefeller Foundation
              Postdoctoral Fellow served as Social Scientist for West Africa for the International Potato Center,
              promoting the post-harvest uses of sweet potato in the bakery and confectionery sector, and strengthening
              of seed potato systems in Cameroon.
            </p>
            <p>
              An Urban Studies graduate of College of St. Catherine, St. Paul Minnesota, she has a Master of City and
              Regional Planning Degree from University of California at Berkeley and Doctor of Philosophy degree from
              University of Oxford (St. Antony’s College) which she attended as the first Rhodes Scholar from Kenya.
              She’s also attended the Executive Development Program at Northwestern University, Kellogg School of Management.
              Dr. Odaga is a director at Community Life Project and Alluvial Trade and Investment. She is also a member of
              the Global Advisory Council of the United Nations Population Fund, UNFPA.
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
  name: 'AdhiamboOdaga'
}
</script>

<style src="../../assets/css/leadership.css"></style>

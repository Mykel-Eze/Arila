<template>
  <div id="join-us-page">
    <!---=== Home Section ===--->
    <section id="join-us-home">
      <div class="row full-height">
        <div class="container full-height rel">
          <div class="leadership-home-txt">
            <h2 class="section-title">
              Join us and <br class="hidden-xs-sm"> make a difference
            </h2>
            <p class="leadership-home-desc">
              Some of Africa’s most eminent leaders are core to our team, providing invaluable
              advice and connections, and influencing public policy interaction.
            </p>
          </div>

          <a href="#top-biography" class="hover-scroll-btn">
            <img src="~/assets/images/scroll-button.svg" alt="scroll">
          </a>
        </div>
      </div>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== Join-Us-Collapsible Section ===--->
    <section id="join-us-collapsible">
      <div class="row">
        <div class="container">
          <div class="ju-collapsible-wrapper">
            <ul class="collapsible">
              <li class="active">
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>Business Owners</span>
                  <img src="~/assets/images/down-arr-green.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="ju-txt">
                    We enable SMEs, logistics companies, farms and other businesses to take the next steps to growth
                    and development.
                  </p>
                  <p class="ju-txt">
                    Through our network of resource, equipment and service providers, we offer a transparent choice of
                    verified and reliable solutions providers. We help efficient business decision making through, for
                    example, offsetting the need to seek pricing from 100 different truck owners for a transport assignment.
                  </p>
                  <p class="ju-txt">
                    We service every aspect of business activity, from verifying the quality of inputs to accessing
                    loans or insurance.
                  </p>
                  <p class="ju-txt">
                    For logistics services providers, we offer visibility across thousands of businesses across the continent,
                    allowing owners to assess and cater to demand, with transparency on the financing available to pay for the
                    services.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>Government & Public Institutions</span>
                  <img src="~/assets/images/down-arr-green.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="ju-txt">
                    The Arila commitment to absolute transparency and meaningful scale translates to increased and diversified tax revenue for governments.
                  </p>
                  <p class="ju-txt">
                    This revenue comes from businesses that often would otherwise have remained in the informal sector.
                  </p>
                  <p class="ju-txt">
                    The implications for sustainable economic growth and development are clear. Our objectives align with
                    specific progress on each of the UN’s 17 SDG’s, including ending poverty and hunger, good health and
                    well being, quality education and gender equality.
                  </p>
                  <p class="ju-txt">
                    This is why established intergovernmental institutions and NGOs, such as USAID and Mercy Corps,
                    have chosen to partner with Arila.
                  </p>
                  <p class="ju-txt">
                    This is why established intergovernmental institutions and NGOs, such as USAID and Mercy Corps,
                    have chosen to partner with Arila.
                  </p>
                  We currently serve businesses across east and west Africa, and our network is developing in southern Africa.
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>Investors & Banks</span>
                  <img src="~/assets/images/down-arr-green.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="ju-txt">
                    The Arila Group aligns impact at meaningful scale with a transparent model for significant and
                    sustained revenue.
                  </p>
                  <p class="ju-txt">
                    Arila owns a majority stake in each of the family of eight operating companies, working across
                    diverse and uncorrelated sectors.
                  </p>
                  <p class="ju-txt">
                    While Arila coordinates the subsidiary companies to maximise synergies, each company has its
                    own independent P&L and additionally pursues business interests beyond the Arila network.
                  </p>
                  <p class="ju-txt">
                    The companies are paid for services provided to the customer; for example, Japtini Logistics
                    is paid by the farmer wanting their produce transported.
                  </p>
                  <p class="ju-txt">
                    Our objectives align with specific progress on each of the UN’s 17 SDG’s.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>Job Opportunities</span>
                  <img src="~/assets/images/down-arr-green.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="ju-txt">
                    We are growing at a pace and recruiting at a pace to match.
                  </p>
                  <p class="ju-txt">
                    Arila and its eight subsidiary companies currently serve businesses across east
                    and west Africa, and we are expanding into southern Africa.
                  </p>
                  <p class="ju-txt">
                    We are keen to hear from self-starters with the drive and ambition to transform
                    the economic and social environment on our continent. We have opportunities across
                    multiple disciplines and geographies.
                  </p>
                  <p class="ju-txt">
                    We are committed to delivering equal opportunities and target 70% female employees,
                    with a focus on youth and under-served communities.
                  </p>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Join-Us-Collapsible Section ===--->
  </div>
</template>

<script>
export default {
  name: 'JoinUsPage',
  mounted () {
    const M = require('materialize-css')

    const elemsCollapsible = document.querySelectorAll('.collapsible')
    M.Collapsible.init(elemsCollapsible)
  }
}
</script>

<style src="../assets/css/join-us.css"></style>
<style src="../assets/css/leadership.css"></style>

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
                  <span>Investors & Banks</span>
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
                  <span>Job Opportunities</span>
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

<template>
  <footer class="bg-light-gray has-shapes has-bg-brash bg-brash-top"
          style="padding-top: 55px;">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-7 col-md-12">
          <div class="text-center pb-60">
            <span class="text-primary-color section-title fw-extra-bold fs-36">Subscribe To Our Mailing List</span>
            <form action="" method="post" name="mc-embedded-subscribe-form" target="_blank" class="needs-validation" style="margin-top: 45px;">
              <div class="input-group">
                <input type="email" class="form-control bg-gray input-email" placeholder="Your email address" required>
                <div class="input-group-append ml-0">
                  <button type="submit" class="btn btn-primary" style="width: 82px;" name="subscribe"><svg width="22" height="16" viewBox="0 0 31 16"
                                                                                                           fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M30.7071 8.70808C31.0976 8.31756 31.0976 7.68439 30.7071 7.29387L24.3431 0.929909C23.9526 0.539384 23.3195 0.539384 22.9289 0.929909C22.5384 1.32043 22.5384 1.9536 22.9289 2.34412L28.5858 8.00098L22.9289 13.6578C22.5384 14.0484 22.5384 14.6815 22.9289 15.072C23.3195 15.4626 23.9526 15.4626 24.3431 15.072L30.7071 8.70808ZM0 9.00098H30V7.00098H0V9.00098Z"
                        fill="white" /></svg></button>
                </div>
              </div>
              <div style="position: absolute; left: -5000px;" aria-hidden="true">
                <input type="text" name="mailchimp_form_name" tabindex="-1">
              </div>
            </form>
          </div>
        </div>
        <div class="col-12">
          <div class="border-bottom"></div>
        </div>
      </div>
      <div class="row pt-60 pb-60">
        <div class="col-lg-5 col-md-6">
          <div class="pr-0 pr-lg-4">
            <a class="mb-25" href="#">
              <img class="img-fluid mb-4" src="@/assets/images/logo/logo.png">
            </a>
            <p>
              STFIL is a liquidity pledge protocol built on top of Filecoin that is designed to be community-owned, decentralized, and trust-free, allowing users to earn block rewards without locking up assets or maintaining Storage Provider infrastructure.
            </p>
          </div>
        </div>
        <div class="col-lg-2 col-md col-sm-6">
          <div class="pl-0 pl-md-3 mt-5 mt-md-0">
            <h5 class="font-weight-600 mb-20">Social Links</h5>
            <ul class="list-unstyled footer-links">
              <li><a href="#">GitHub</a></li>
              <li><a href="#">Forum</a></li>
              <li><a href="#">Twitter</a></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-2 col-md col-sm-6">
          <div class="pl-0 pl-md-3 mt-5 mt-md-0">
            <h5 class="font-weight-600 mb-20">Learn</h5>
            <ul class="list-unstyled footer-links">
              <li><a href="#">Introduction</a></li>
              <li><a href="#">Guides</a></li>
              <li><a href="#">Developers</a></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-2 col-md col-sm-6">
          <div class="pl-0 pl-md-3 mt-5 mt-md-0">
            <h5 class="font-weight-600 mb-20">Quick Links</h5>
            <ul class="list-unstyled footer-links">
              <li><a href="#">Terms & Conditions</a></li>
              <li><a href="#">Privacy Policy</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="block border-top text-center content">©2022 STFIL All rights reserved.</div>
          </div>
        </div>
      </div>
    </div>

    <div class="shape-1 shape-xs bg-orange rounded-circle"></div>
    <div class="shape-2 shape-sm-2 bg-cyan rounded-circle"></div>
    <div class="shape-3 shape-sm bg-yellow rounded-circle"></div>
    <div class="shape-4 shape-xs-2 bg-cyan rounded-circle"></div>
    <div class="shape-5 shape-sm-2 bg-yellow rounded-circle"></div>
    <div class="shape-6 shape-sm-2 bg-orange rounded-circle"></div>
  </footer>
</template>

<script>
export default {
  name: "IFooter"
}
</script>

<style scoped>

</style>

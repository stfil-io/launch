<template>
  <div class="home-class">
    <section class="section-padding pt-0 horizontal-accordion ">
      <div class="container h-100">
        <div class="row justify-content-center">
          <div class="col-lg-10 col-md-9 text-center title-padding-top">
            <div class="fw-extra-bold  index-title">{{ $t('title') }}</div>
            <div class="fw-extra-bold  index-title">{{ $t('title2') }}</div>
            <div class="launch-margin-top">
              <img class="launch-icon-size" src="@/assets/images/launched.png" alt="">
              <span class="fw-medium fs-18">{{ $t('stage') }}: LAUNCHED</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section-padding bg-white">
      <div class="bg-white container h-100">
        <div class="has-colored-text row justify-content-center colored-icon-box">
          <div class="col-lg-6 col-md-12 col-12 mb-30">
            <div class="rounded p-2 p-lg-5 aos-init aos-animate" data-aos="fade-up" data-aos-delay="50"
                 style="height: 100%;">
              <h3 class="mb-2 mb-lg-4 fw-extra-bold sub-title text-primary-color">{{ $t('the-offer') }}</h3>
              <div class="margin-top-50 margin-md-top-20">
                <div class="row align-items-center mb-2 margin-top-25">
                  <div class="col-4 fs-16 text-primary-color-60">{{ $t('total') }}</div>
                  <div class="col-8 text-right text-md-right text-lg-left">
                    <h5 class="fw-extra-bold text-primary-color  fs-18">500,000 stFIL</h5>
                  </div>
                </div>
                <div class="row align-items-center mb-2 margin-top-25">
                  <div class="col-4 fs-16 text-primary-color-60">{{ $t('slots') }}</div>
                  <div class="col-8 text-right text-md-right text-lg-left">
                    <h5 class="fw-extra-bold text-primary-color  fs-18">1,000</h5>
                  </div>
                </div>
                <div class="row align-items-center mb-2 margin-top-25">
                  <div class="col-4 fs-16 text-primary-color-60">
                    {{ $t('price-per-slot') }}
                  </div>
                  <div class="col-8 text-right text-md-right text-lg-left">
                    <h5 class="fw-extra-bold text-primary-color  fs-18">500 FIL</h5>
                  </div>
                </div>
                <div class="row align-items-center mb-2 margin-top-25">
                  <div class="col-4 fs-16 text-primary-color-60">{{ $t('start-time') }}
                  </div>
                  <div class="col-8 text-right text-md-right text-lg-left">
                    <h5 class="fw-extra-bold text-primary-color fs-18">2023/02/01 8:00:00 UTC</h5>
                  </div>
                </div>
                <div class="row align-items-center mb-2 margin-top-25">
                  <div class="col-4 fs-16 text-primary-color-60">{{ $t('end-time') }}
                  </div>
                  <div class="col-8 text-right text-md-right text-lg-left">
                    <h5 class="fw-extra-bold text-primary-color fs-18">2023/02/14 8:00:00 UTC</h5>
                  </div>
                </div>

                <div class="align-items-center mb-2 margin-top-25">
                  <div class="font-weight-bold text-primary d-flex align-items-center" style="cursor: pointer">
                    <div>{{ $t('More-about-the-token-mics') }}</div>
                    <img src="@/assets/images/icons/more.png" alt="" style="width: 8px;" class="ml-2">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6 col-md-12 col-12 mb-30">
            <div class="rounded  p-2 p-lg-5 p-md-5 p-sm-4 aos-init aos-animate" data-aos="fade-up" data-aos-delay="50"
                 style="height: 100%;">
              <h3 class="mb-2 mb-lg-4 fw-extra-bold sub-title text-primary-color">{{ $t('the-return') }}</h3>
              <div class="margin-top-50 margin-md-top-20">
                <div class="row align-items-center mb-2 margin-top-25">
                  <div class="col-4 fw-medium fs-16 text-primary-color-60">{{ $t('fdo-token') }}</div>
                  <div class="col-8 text-right text-md-right text-lg-left">
                    <h5 class="fw-extra-bold text-primary-color fs-18">500 stFIL + 15,000 FDO</h5>
                  </div>
                </div>
                <div class="row align-items-center mb-2 margin-top-25">
                  <div class="col-6 col-md-4 fw-medium fs-16 text-primary-color-60">{{ $t('founder-nft') }}</div>
                  <div class="col-6 col-md-8 text-right text-md-right text-lg-left">
                    <h5 class="fw-extra-bold text-primary-color">1/1000</h5>
                  </div>
                </div>
                <div class="row align-items-center mt-4 mb-2 margin-top-25">
                  <div class="col-lg-4 col-md-4"></div>
                  <div class="col-12 col-lg-8 col-md-8 text-right text-md-right text-lg-left">
                    <div class="d-inline-block">
                      <img class="img-fluid rounded-sm" src="@/assets/images/nft.png" alt="">
                    </div>
                    <p class="mt-2 fw-medium fs-16 text-left">
                      {{ $t('claim-for-free-when-ready') }}
                    </p>
                    <div class="font-weight-bold text-primary d-flex align-items-center mt-1" style="cursor: pointer">
                      <div>{{ $t('more-about-this') }}</div>
                      <img src="@/assets/images/icons/more.png" alt="" style="width: 8px;" class="ml-2">
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section-padding pt-0 bg-white">
      <div class="container">
        <div class="alert alert-danger alert-pink p-lg-5" style="">
          <div class="row pt-lg-0 pt-sm-2 pb-sm-2 justify-content-center align-items-center">
            <div class="col-lg-3 col-md-12 col-sm-12 mt-2 mt-lg-0">
              <div class="row justify-content-center align-items-center">
                <div class="col-lg-12 col-md-6 col-sm-6 col-6 text-lg-center">
                  <h6 class="fw-medium text-primary-color-60">{{ $t('sale-stage') }}</h6>
                </div>
                <div class="col-lg-12 col-md-6 col-sm-6 mt-lg-2 col-6 text-right text-md-right text-lg-center">
                  <h5 class="fw-extra-bold text-primary-color">Launched</h5>
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-md-12 col-sm-12 mt-2 mt-lg-0">
              <div class="row  justify-content-center align-items-center">
                <div class="col-lg-12 col-md-6 col-sm-6 col-6 text-lg-center">
                  <h6 class="fw-medium text-primary-color-60">{{ $t('WHITELISTED') }}</h6>
                </div>
                <div class="col-lg-12 col-md-6 col-sm-6 col-6 mt-lg-2 text-right text-md-right text-lg-center">
                  <h5 class="fw-extra-bold text-primary-color">0</h5>
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-md-12 mt-2 mt-lg-0">
              <div class="row  justify-content-center align-items-center">
                <div class="col-lg-12 col-md-6 col-sm-6 col-6 text-lg-center">
                  <h6 class="fw-medium text-primary-color-60">{{ $t('slots-left') }}</h6>
                </div>
                <div class="col-lg-12 col-md-6 col-sm-6 col-6 mt-lg-2 text-right text-md-right text-lg-center">
                  <h5 class="fw-extra-bold text-primary-color">0/1000</h5>
                </div>
              </div>
            </div>
            <div
                class="col-lg-3 col-md-12 col-sm-12 text-lg-right text-md-center text-sm-center text-center mt-4 mt-lg-0">
              <button disabled class="btn i-btn-primary btn-sm" type="submit">Launched</button>
            </div>
          </div>
        </div>
      </div>
      <div class="container">
        <p class="fw-regular fs-14" style="opacity: 0.6;">{{ $t('tip') }}</p>
      </div>
    </section>
    <section class="section-padding pt-0 bg-white">
      <div class="container">
        <nav>
          <div class="nav nav-tabs" id="nav-tab" role="tablist">
            <button class="nav-link nav-link-none text-primary-color-60 fs-16 fw-medium active" id="nav-home-tab"
                    data-toggle="tab" data-target="#nav-home" type="button" role="tab" aria-controls="nav-home"
                    aria-selected="true">{{ $t('faq') }}
            </button>
            <button class="nav-link nav-link-none text-primary-color-60 fs-16 fw-medium" id="nav-profile-tab"
                    data-toggle="tab" data-target="#nav-profile" type="button" role="tab" aria-controls="nav-profile"
                    aria-selected="false">{{ $t('whitelisted') }}
            </button>
          </div>
        </nav>
        <div class="tab-content" id="nav-tabContent">
          <div class="text-primary-color tab-pane fade show active mt-4 md-class markdown-body"
               style="font-weight: normal"
               id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab">
            <template v-if="$i18n.locale === 'en'">
              <enMd></enMd>
            </template>
            <template v-if="$i18n.locale === 'zh'">
              <cnMd></cnMd>
            </template>
          </div>
          <div class="text-primary-color tab-pane fade" id="nav-profile" role="tabpanel"
               aria-labelledby="nav-profile-tab">
            <div class="tab-pane fade show active mt-5"
                 style="font-weight: normal"
                 id="nav-home-2" role="tabpanel" aria-labelledby="nav-home-tab">
              <div class="text-primary-color form-group mb-30">
                <label class="fw-medium fs-16 mb-2">{{ $t('address-filter') }}</label>
                <input class="form-control shadow-none mt-1 i-form-control" type="text" placeholder="Your address"
                       id="fname" required="">
                <label class="fw-medium fs-14 mb-2 mt-2 text-primary-color-60">{{ $t('tip2') }}</label>
              </div>
              <div class="text-primary-color container text-center fw-medium pt-5 text-primary-color-60">
                {{ $t('can-find-the-address') }}
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import 'github-markdown-css'
import enMd from '@/assets/md/en/wt.md'
import cnMd from '@/assets/md/cn/wt.md'

export default {
  name: 'HomeView',
  components: {enMd, cnMd},
  data() {
    return {
      tabs: {
        check: 0,
        list: [
          {
            label: '常见问题',
            id: 'a'
          },
          {
            label: '白名单',
            id: 'b'
          }
        ]
      }
    }
  }
}
</script>

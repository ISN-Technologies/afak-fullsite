<template>
  <section class="banner-slide">

    <VueSlickCarousel v-bind="settings">
      <div class="banner-area slide-bg1 bg_cover d-flex align-items-center">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-lg-10">
              <div class="banner-content text-center">
                <span data-animation="fadeInDown" data-delay="1s">Construction Materials Supply</span>
                <h3 data-animation="fadeInDown" data-delay=".1s" class="title">We provide you the construction materials you need.</h3>
                <nuxt-link class="main-btn" to="/service-construction">Learn More</nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="banner-area slide-bg2 bg_cover d-flex align-items-center">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-lg-10">
              <div class="banner-content text-center">
                <span data-animation="fadeInDown" data-delay="1s">Real Estate</span>
                <h3 data-animation="fadeInDown" data-delay=".1s" class="title">Buy your dream house at our prime locations.</h3>
                <nuxt-link class="main-btn" to="/service-realestate">Learn More</nuxt-link>

              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="banner-area slide-bg3 bg_cover d-flex align-items-center">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-lg-10">
              <div class="banner-content text-center">
                <span data-animation="fadeInDown" data-delay="1s">Mining</span>
                <h3 data-animation="fadeInDown" data-delay=".1s" class="title">We provide you with the best mining service.</h3>
                <nuxt-link class="main-btn" to="/service-mining">Learn More</nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>

    </VueSlickCarousel>
  </section>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'

export default {
  name: "Banner",
  components: {VueSlickCarousel},
  data() {
    return {
      settings: {
        arrows: false,
        autoplay: true
      },
    }
  },
}
</script>

<style scoped>

</style>

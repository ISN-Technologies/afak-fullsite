<template>
  <section class="services-area">
    <div class="container">
      <div class="services-bg">
        <div class="row">
          <div class="col-lg-3 col-md-6 col-sm-6">
            <div class="services-item mt-50">
              <img src="/assets/images/logistics-mini.jpg" alt="logistics">
              <div class="services-overlay">
                <h4 class="title">Logistics</h4>
                <p>We ensure that your goods are delivered to you on time.</p>
                <nuxt-link to="/service-logistics">Learn More</nuxt-link>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6">
            <div class="services-item mt-50">
              <img src="/assets/images/mining-mini.jpg" alt="mining">
              <div class="services-overlay">
                <h4 class="title">Mining</h4>
                <p>We provide quality mining service.</p>
                <nuxt-link to="/service-mining">Learn More</nuxt-link>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6">
            <div class="services-item mt-50">
              <img src="/assets/images/construction-mini.jpg" alt="construction">
              <div class="services-overlay">
                <h4 class="title">Construction Material Supply</h4>
                <p>We supply construction materials you need.</p>
                <nuxt-link to="/service-construction">Learn More</nuxt-link>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-6">
            <div class="services-item mt-50">
              <img src="/assets/images/realestate-mini.jpg" alt="realestate">
              <div class="services-overlay">
                <h4 class="title">Real Estate</h4>
                <p>Own a property in a premium and secure environment.</p>
                <nuxt-link to="/service-realestate">Learn More</nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="services-shape">
      <img src="/assets/images/shape/shape-7.png" alt="">
    </div>
  </section>
</template>

<script>
    export default {
        name: "ServiceArea"
    }
</script>

<style scoped>

</style>

<template>
  <section class="industri-services-area">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="services-title text-center">
            <h3 class="title">What we Do</h3>
            <p style="margin-top: 10px; font-size: 20px">
              We pride ourselves with provision of high quality and service above and beyond customer expectations in
              the following areas:
            </p>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-4 col-md-6 col-sm-9">
          <div class="services-item mt-30">
            <div class="services-thumb">
              <img src="/assets/images/services/construction.png" alt="">
              <!--              <div class="icon">-->
              <!--                <i class="flaticon-under-construction"></i>-->
              <!--              </div>-->
            </div>
            <div class="services-content">
              <h4 class="title">Construction Material Supply</h4>
              <!--              <p>There are many variations of passages of available but the have alteration in not avein that some form by injected.</p>-->
              <!--              <nuxt-link to="/single-service">Read More</nuxt-link>-->
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-9">
          <div class="services-item mt-30">
            <div class="services-thumb">
              <img src="/assets/images/services/mining.png" alt="">
              <!--              <div class="icon">-->
              <!--                <i class="flaticon-industry"></i>-->
              <!--              </div>-->
            </div>
            <div class="services-content">
              <h4 class="title">Mining</h4>
              <!--              <p>There are many variations of passages of available but the have alteration in not avein that some form by injected.</p>-->
              <!--              <nuxt-link to="/single-service">Read More</nuxt-link>-->
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-9">
          <div class="services-item mt-30">
            <div class="services-thumb">
              <img src="/assets/images/services/logistics.png" alt="">
              <!--              <div class="icon">-->
              <!--                <i class="flaticon-layout"></i>-->
              <!--              </div>-->
            </div>
            <div class="services-content">
              <h4 class="title">Logistics</h4>
            </div>
          </div>
        </div>
      </div>
      <div class="row justify-content-center" style="margin-top: 10px; gap: 6px">
        <nuxt-link class="main-btn"  to="/services">View All Services</nuxt-link>
        <nuxt-link class="main-btn main-btn-2" to="/contact">Request Quote</nuxt-link>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: "ServicesArea"
}
</script>

<style scoped>

</style>

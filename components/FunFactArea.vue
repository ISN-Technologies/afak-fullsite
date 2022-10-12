<template>
  <section class="fun-facts-area" v-observe-visibility="onVisibilityChange">
    <div class="container">
      <div class="fun-facts-bg">
        <div class="row">
          <div class="col-lg-3 col-md-6">
            <div class="fun-facts-item text-center mt-30 animated wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="0ms">
              <h3 class="title odometer"><countTo :startVal='0' :endVal='startCounter ? 20 : 0' :duration='3000'></countTo></h3>
              <span>Projects Completed</span>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="fun-facts-item text-center mt-30 animated wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="100ms">
              <h3 class="title odometer"><countTo :startVal='0' :endVal='startCounter ? 10 : 0' :duration='3000'></countTo></h3>
              <span>Skilled Contractors</span>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="fun-facts-item text-center mt-30 animated wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="200ms">
              <h3 class="title odometer"><countTo :startVal='0' :endVal='startCounter ? 12 : 0' :duration='3000'></countTo></h3>
              <span>Industries Served</span>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="fun-facts-item text-center mt-30 animated wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="300ms">
              <h3 class="title odometer"><countTo :startVal='0' :endVal='startCounter ? 100 : 0' :duration='3000'></countTo></h3>
              <span>satisfied clients</span>
            </div>
          </div>
        </div>
<!--        <div class="shape">-->
<!--          <img src="/assets/images/shape/shape-17.png" alt="shape">-->
<!--        </div>-->
      </div>
    </div>
  </section>
</template>

<script>
  import countTo from 'vue-count-to';
  import { ObserveVisibility } from 'vue-observe-visibility'
  export default {
    name: "FunFactArea",
    components: { countTo },
    directives: {
      ObserveVisibility
    },
    data() {
      return{
        startCounter: false
      }
    },
    methods: {
      onVisibilityChange (isVisible) {
        if (isVisible){
          this.startCounter = true;
        }

      },
    }
  }
</script>

<style scoped>

</style>

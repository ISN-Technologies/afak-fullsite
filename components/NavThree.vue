<template>
  <header class="header-area header-3-area">
    <div class="header-top-3">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="header-top-item">
              <div class="header-info">
                <ul>
                  <li><a href="mailto:info@afaktanzania.co.tz"><i class="flaticon-email-2"></i> info@afaktanzania.co.tz</a></li>
<!--                  <li><a href="tel: +255766767210"><i class="flaticon-call"></i> +255 766 767 210</a></li>-->
                  <li><a href="tel: ++255757581111"><i class="flaticon-call"></i> +255 757 581 111</a></li>
                  <li><a href=""><i class="flaticon-pin"></i> Amverton Tower, Masaki, Dar es Salaam, Tanzania </a></li>
                </ul>
              </div>
              <div class="social">
                <ul>
                  <li><a href="https://facebook.com/afaktz"><i class="fa fa-facebook-f"></i></a></li>
                  <li><a href="https://twitter.com/afaktz"><i class="fa fa-twitter"></i></a></li>
                  <li><a href="https://instagram.com/afaktz"><i class="fa fa-instagram"></i></a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="main-header">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="main-header-item">
              <div class="main-header-menus  d-flex justify-content-between align-items-center">
                <div class="header-logo">
                  <a href="/"><img src="/assets/images/logo.png" alt="logo"></a>
                </div>
                <div class="toggle-btn ml-30 canvas_open">
                  <i @click="mobileToggle = !mobileToggle" class="fa fa-bars"></i>
                </div>
                <div class="header-menu d-none d-lg-block">
                  <ul>
                    <li>
                      <a href="/">Home</a>
                    </li>
                    <li>
                      <a href="#">About</a>
                      <ul class="sub-menu">
                        <li>
                          <nuxt-link to="/about">About Us</nuxt-link>
                        </li>
<!--                        <li>-->
<!--                          <nuxt-link to="/our-mission">Our Mission</nuxt-link>-->
<!--                        </li>-->
                        <!--                        <li>-->
                        <!--                          <nuxt-link to="/our-history">Our Story</nuxt-link>-->
                        <!--                        </li>-->
                        <!--                        <li>-->
                        <!--                          <nuxt-link to="/testimonials">Testimonials</nuxt-link>-->
                        <!--                        </li>-->
                      </ul>
                    </li>
                    <li>
                      <nuxt-link to="/services">Our Services</nuxt-link>
<!--                      <ul class="sub-menu">-->
<!--                        <li>-->
<!--                          <nuxt-link to="/services">Services</nuxt-link>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                          <nuxt-link to="/service-logistics">Logistics</nuxt-link>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                          <nuxt-link to="/service-construction">Construction Material Supply</nuxt-link>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                          <nuxt-link to="/service-realestate">Real Estate</nuxt-link>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                          <nuxt-link to="/service-mining">Mining</nuxt-link>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                          <nuxt-link to="/service-softwaresolutions">Software Solutions</nuxt-link>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                          <nuxt-link to="/service-professionalconsultancy">Professional Consultancy</nuxt-link>-->
<!--                        </li>-->
<!--                      </ul>-->
                    </li>
<!--                    <li>-->
<!--                      <nuxt-link to="/projects">Projects</nuxt-link>-->
<!--                    </li>-->
                    <li>
                      <nuxt-link to="/contact">Contact Us</nuxt-link>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div :class="`offcanvas_menu_wrapper ${mobileToggle ? 'active' : ''}`">
              <div class="canvas_close">
                <a @click="mobileToggle = !mobileToggle" href="javascript:void(0)"><i class="fa fa-times"></i></a>
              </div>
              <div class="header-social">
                <ul class="text-center">
                  <li><a href="https://facebook.com/afaktz"><i class="fa fa-facebook-f"></i></a></li>
                  <li><a href="https://twitter.com/afaktz"><i class="fa fa-twitter"></i></a></li>
                  <li><a href="https://instagram.com/afaktz"><i class="fa fa-instagram"></i></a></li>
                </ul>
              </div>
              <div id="menu" class="text-left ">
                <ul class="offcanvas_main_menu">
                  <li class="menu-item-has-children active">
                    <a href="/">Home</a>
                  </li>
                  <li class="menu-item-has-children active"><span class="menu-expand"><i
                    class="fa fa-angle-down"></i></span>
                    <a href="#">About</a>
                    <ul class="sub-menu">
                      <li>
                        <nuxt-link to="/about">About Us</nuxt-link>
                      </li>
<!--                      <li>-->
<!--                        <nuxt-link to="/our-mission">Our Mission</nuxt-link>-->
<!--                      </li>-->
                      <!--                      <li>-->
                      <!--                        <nuxt-link to="/our-history">Our Story</nuxt-link>-->
                      <!--                      </li>-->
                      <!--                      <li>-->
                      <!--                        <nuxt-link to="/testimonials">Testimonials</nuxt-link>-->
                      <!--                      </li>-->
                    </ul>
                  </li>
<!--                  <li class="menu-item-has-children active"><span class="menu-expand"><i-->
<!--                    class="fa fa-angle-down"></i></span>-->
                  <li>
                    <nuxt-link to="/services">Our Services</nuxt-link>
                  </li>
<!--                    <ul class="sub-menu">-->
<!--                      <li>-->
<!--                        <nuxt-link to="/services">Services</nuxt-link>-->
<!--                      </li>-->
<!--                      <li>-->
<!--                        <nuxt-link to="/service-logistics">Logistics</nuxt-link>-->
<!--                      </li>-->
<!--                      <li>-->
<!--                        <nuxt-link to="/service-construction">Construction Material Supply</nuxt-link>-->
<!--                      </li>-->
<!--                      <li>-->
<!--                        <nuxt-link to="/service-realestate">Real Estate</nuxt-link>-->
<!--                      </li>-->
<!--                      <li>-->
<!--                        <nuxt-link to="/service-mining">Mining</nuxt-link>-->
<!--                      </li>-->
<!--                      <li>-->
<!--                        <nuxt-link to="/service-softwaresolutions">Software Solutions</nuxt-link>-->
<!--                      </li>-->
<!--                      <li>-->
<!--                        <nuxt-link to="/service-professionalconsultancy">Professional Consultancy</nuxt-link>-->
<!--                      </li>-->
<!--                    </ul>-->
<!--                  </li>-->
<!--                  <li class="menu-item-has-children active">-->
<!--                    <nuxt-link to="/projects">Projects</nuxt-link>-->
<!--                  </li>-->
                  <!--                  <li class="menu-item-has-children active"><span class="menu-expand"><i class="fa fa-angle-down"></i></span>-->
                  <!--                    <a href="#">Blog</a>-->
                  <!--                    <ul class="sub-menu">-->
                  <!--                      <li><nuxt-link to="/posts">posts</nuxt-link></li>-->
                  <!--                      <li><nuxt-link to="/single-post">single post</nuxt-link></li>-->
                  <!--                    </ul>-->
                  <!--                  </li>-->
                  <li class="menu-item-has-children active">
                    <nuxt-link to="/contact">Contact Us</nuxt-link>
                  </li>
                </ul>
              </div>
              <div class="offcanvas_footer">
                <span><a href="mailto:info@afaktanzania.co.tz"><i
                  class="fa fa-envelope-o"></i> AFAK Tanzania Ltd</a></span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
    export default {
      name: "NavThree",
      data(){
        return {
          mobileToggle: false
        }
      },
    }
</script>

<style scoped>

</style>

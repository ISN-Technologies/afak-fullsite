<template>
  <header class="header-area">
    <div class="header-top">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="header-top-items d-flex justify-content-between align-items-center">
              <div class="logo">
                <a href="/"><img src="/assets/images/logo.png" alt=""></a>
              </div>
              <div class="header-top-info d-none d-md-block">
                <ul>
                  <li>
                    <i class="flaticon-email"></i>
                    <span>Email</span>
                    <a href="mailto:info@afaktanzania.co.tz">info@afaktanzania.co.tz</a>
                  </li>
                  <li>
                    <i class="flaticon-calling"></i>
                    <span>Phone</span>
                    <a href="tel:+255755270604">+255 755 270 604</a>
                    <hr/>
                    <a href="tel: +255766767210"> +255 766 767 210</a>
                  </li>
                  <li>
                    <i class="flaticon-address"></i>
                    <span>Visit Us</span>
                    <a href="#">Amvertoon Tower, Masaki, Dar es Salaam</a>
                  </li>
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
            <div class="main-header-item d-flex justify-content-between align-items-center">
              <div class="main-header-menus  d-flex">
                <div class="header-btn">
                  <a href="#"> Lets Discuss Your Project</a>
                </div>
                <div class="toggle-btn ml-30 canvas_open">
                  <i @click="mobileToggle = !mobileToggle" class="fa fa-bars"></i>
                </div>
                <div class="header-menu d-none d-lg-block">
                  <ul>
                    <li>
                      <a class="active" href="#">Home</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/">Home 1</nuxt-link></li>
                        <li><nuxt-link to="/index-2">Home 2</nuxt-link></li>
                        <li><nuxt-link to="/index-3">Home 3</nuxt-link></li>
                        <li>
                          <a href="#">Header Versions</a>
                          <ul class="sub-menu">
                            <li><nuxt-link to="/">Header Style 1</nuxt-link></li>
                            <li><nuxt-link to="/index-2">Header Style 2</nuxt-link></li>
                            <li><nuxt-link to="/index-3">Header Style 3</nuxt-link></li>
                          </ul>
                        </li>
                      </ul>
                    </li>
                    <li>
                      <a href="#">Pages</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/about">About</nuxt-link></li>
                        <li><nuxt-link to="/our-team">Our Team</nuxt-link></li>
                        <li><nuxt-link to="/our-history">Our history</nuxt-link></li>
                        <li><nuxt-link to="/testimonials">testimonials</nuxt-link></li>
                      </ul>
                    </li>
                    <li>
                      <a href="#">Services</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/services">Services</nuxt-link></li>
<!--                        <li><nuxt-link to="/single-service">single service</nuxt-link></li>-->
                      </ul>
                    </li>
                    <li>
                      <a href="#">Recent Projects</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/projects">Projects</nuxt-link></li>
                        <li><nuxt-link to="/single-project">single project</nuxt-link></li>
                      </ul>
                    </li>
                    <li>
                      <a href="#">Blog</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/posts">posts</nuxt-link></li>
                        <li><nuxt-link to="/single-post">single post</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link to="/contact">Contact</nuxt-link></li>
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
                  <li><a href="#"><i class="fa fa-facebook-f"></i></a></li>
                  <li><a href="#"><i class="fa fa-twitter"></i></a></li>
                  <li><a href="#"><i class="fa fa-skype"></i></a></li>
                  <li><a href="#"><i class="fa fa-pinterest-p"></i></a></li>
                </ul>
              </div>
              <div id="menu" class="text-left ">
                <ul class="offcanvas_main_menu">
                  <li class="menu-item-has-children active"><span class="menu-expand"><i class="fa fa-angle-down"></i></span>
                    <a href="#">Home</a>
                    <ul class="sub-menu">
                      <li><nuxt-link to="/">Home 1</nuxt-link></li>
                      <li><nuxt-link to="/index-2">Home 2</nuxt-link></li>
                      <li><nuxt-link to="/index-3">Home 3</nuxt-link></li>
                      <li class="menu-item-has-children"><span class="menu-expand"><i class="fa fa-angle-down"></i></span>
                        <a href="#">Header Versions</a>
                        <ul class="sub-menu">
                          <li><nuxt-link to="/">Header Style 1r</nuxt-link></li>
                          <li><nuxt-link to="/index-2">Header Style 2</nuxt-link></li>
                          <li><nuxt-link to="/index-3">Header Style 3</nuxt-link></li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                  <li class="menu-item-has-children active"><span class="menu-expand"><i class="fa fa-angle-down"></i></span>
                    <a href="#">About</a>
                    <ul class="sub-menu">
                      <li><nuxt-link to="/about">About Us</nuxt-link></li>
                      <li><nuxt-link to="/our-team">Our Team</nuxt-link></li>
                      <li><nuxt-link to="/our-history">Our history</nuxt-link></li>
                      <li><nuxt-link to="/testimonials">Testimonials</nuxt-link></li>
                    </ul>
                  </li>
                  <li class="menu-item-has-children active"><span class="menu-expand"><i class="fa fa-angle-down"></i></span>
                    <a href="#">Services</a>
                    <ul class="sub-menu">
                      <li><nuxt-link to="/services">Services</nuxt-link></li>
                      <li><nuxt-link to="/single-service">single service</nuxt-link></li>
                    </ul>
                  </li>
                  <li class="menu-item-has-children active"><span class="menu-expand"><i class="fa fa-angle-down"></i></span>
                    <a href="#">Recent Projects</a>
                    <ul class="sub-menu">
                      <li><nuxt-link to="/projects">Projects</nuxt-link></li>
                      <li><nuxt-link to="/single-project">single project</nuxt-link></li>
                    </ul>
                  </li>
<!--                  <li class="menu-item-has-children active"><span class="menu-expand"><i class="fa fa-angle-down"></i></span>-->
<!--                    <a href="#">Blog</a>-->
<!--                    <ul class="sub-menu">-->
<!--                      <li><nuxt-link to="/posts">posts</nuxt-link></li>-->
<!--                      <li><nuxt-link to="/single-post">single post</nuxt-link></li>-->
<!--                    </ul>-->
<!--                  </li>-->
                  <li class="menu-item-has-children active">
                    <a href="#">Contact Us</a>
                  </li>
                </ul>
              </div>
              <div class="offcanvas_footer">
                <span><a href="mailto:tanvirahmed8282@gmail.com"><i class="fa fa-envelope-o"></i> layerdrops@gmail.com</a></span>
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
      name: "Nav",
      data(){
        return {
          mobileToggle: false
        }
      },
    }
</script>

<style scoped>

</style>

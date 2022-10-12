<template>
  <section class="conatct-area pb-115">
    <div class="container">
      <div class="row">
        <div class="col-lg-5">
          <div class="conatct-info">
            <h3 class="title">Work with us</h3>
            <p>Our doors are open for strategic corporate and private partnerships. Let's work together and make something great.</p>
          </div>
          <div class="conatct-info-item">
            <div class="item">
              <i class="flaticon-email"></i>
              <span>Email</span>
              <p>info@afaktanzania.co.tz</p>
            </div>
            <div class="item center">
              <i class="flaticon-calling"></i>
              <span>Phone</span>
              <p>+255 755 270 604 | +255 766 767 210</p>
            </div>
            <div class="item">
              <i class="flaticon-address"></i>
              <span>Visit Us</span>
              <p>Mezzanine Floor, Amverton Tower, Masaki,<br/> Dar es Salaam, Tanzania</p>
            </div>
          </div>
        </div>
        <div class="col-lg-7">
          <div class="comment-form">
            <form action="#" method="POST" class="contact-one__form" id="contact-form">
              <div class="row">
                <div class="col-lg-6">
                  <div class="input-box">
                    <input type="text" placeholder="Your name" name="name">
                  </div>
                </div><!-- /.col-lg-6 -->
                <div class="col-lg-6">
                  <div class="input-box">
                    <input type="email" placeholder="Email Address" name="email">
                  </div>
                </div><!-- /.col-lg-6 -->
                <div class="col-lg-6">
                  <div class="input-box">
                    <input type="text" placeholder="Phone number" name="number">
                  </div>
                </div><!-- /.col-lg-6 -->
                <div class="col-lg-6">
                  <div class="input-box">
                    <input type="text" placeholder="Company/Organisation" name="subject">
                  </div>
                </div><!-- /.col-lg-6 -->
                <div class="col-lg-12">
                  <div class="input-box">
                    <textarea placeholder="Project Details" name="message"></textarea>
                  </div>
                </div><!-- /.col-lg-12 -->
                <div class="col-lg-12 text-left">
                  <div class="input-box">
                    <button type="submit" class="main-btn">Let's Work Together</button>
                  </div>
                  <!-- /.thm-btn contact-one__btn -->
                </div><!-- /.col-lg-12 -->
              </div><!-- /.row -->
            </form><!-- /.contact-one__form -->
            <p class="form-message"></p>
          </div><!-- /.comment-form -->
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ContactPage"
    }
</script>

<style scoped>

</style>

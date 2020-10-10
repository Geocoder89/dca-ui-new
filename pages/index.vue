<template>
  <!-- BEGIN: Content-->
  <div
    class="app-content content justify-content-center"
    style="margin-left:0;"
  >
    <div class="content-overlay"></div>
    <div class="header-navbar-shadow"></div>
    <div class="content-wrapper">
      <div class="content-header row"></div>
      <div class="content-body">
        <section class="card-overlay">

          <div class="card-overlay-img">
              <div
            id="carouselExampleSlidesOnly"
            class="carousel slide"
            data-ride="carousel"
          >
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img class="d-block w-100" src="~assets/img/samples/doctor2.jpg" alt="First slide" />
              </div>
              <div class="carousel-item">
                <img class="d-block w-100" src="~assets/img/samples/doctor2.jpg" alt="Second slide" />
              </div>
              <div class="carousel-item">
                <img class="d-block w-100" src="~assets/img/samples/doctor2.jpg"  alt="Third slide" />
              </div>
            </div>
          </div>
          </div>

        </section>

        <section class="row flexbox-container justify-content-center">
          <div class="col-xl-8 col-11 d-flex justify-content-center">
            <div class="card rounded-0 mb-0">
              <div class="row m-0">
                <div
                  class="col-lg-12"
                  style="display:flex;justify-content: center;"
                >
                  <img
                    src="~assets/img/logo/drapp.png"
                    class="mb-2 mt-1"
                    width="250px"
                    height="80px"
                  />
                  <!-- <h2 class="brand-text mb-2 mt-1" style="align-self: center;">Drcallaway</h2> -->
                </div>
                <div class="col-lg-12 col-12 p-0">
                  <div class="card rounded-0 mb-0 px-2">
                    <!-- <div class="card-header pb-1">
                                            <div class="card-title text-center d-flex justify-content-center">
                                                <h3 class="px-3 text-center align-self-center">Verify Your Account</h3>
                                            </div>
                                        </div> -->
                    <div class="card-title">
                      <!-- <h3 class="text-center">Drcallaway</h3> -->
                    </div>
                    <h2 class=" text-center p">
                      Welcome to a world where we literally treat
                    </h2>
                    <h1 class="text-center display-4">HEALTH AS WEALTH.</h1>

                    <div class="card-content">
                      <div
                        class="card-body pt-1 d-flex justify-content-center flex-wrap"
                      >
                        <!-- Icon, Title and Description Card -->

                        <div class="row">
                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/patients/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                  >
                                    <img
                                      src="~assets/img/icons/09.png"
                                    />Patient</nuxt-link
                                  >
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>

                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/pharmacy/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                  >
                                    <img src="~assets/img/icons/07.png" /> Nurse
                                  </nuxt-link>
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>

                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/doctor/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                    ><img src="~assets/img/icons/05.png" />
                                    Doctor
                                  </nuxt-link>
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>

                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/pharmacy/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                    ><img src="~assets/img/icons/04.png" />
                                    Nutritionist</nuxt-link
                                  >
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>
                        </div>

                        <div class="row">
                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/pharmacy/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                  >
                                    <img src="~assets/img/icons/06.png" />
                                    Diagnostic</nuxt-link
                                  >
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>

                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/pharmacy/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                  >
                                    <img src="~assets/img/icons/03.png" />
                                    Ambulance
                                  </nuxt-link>
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>

                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/pharmacy/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                  >
                                    <img
                                      src="~assets/img/icons/08.png"
                                    />Pharmacy
                                  </nuxt-link>
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>

                          <div class="col-12 col-sm-6 col-md-3">
                            <div class="card pmd-card text-center">
                              <div class="card-body">
                                <div class="pmd-card-icon">
                                  <nuxt-link
                                    to="/pharmacy/signup"
                                    class="card-title"
                                    style="text-align: center;"
                                  >
                                    <img src="~assets/img/icons/02.png" />
                                    Hospital</nuxt-link
                                  >
                                </div>
                              </div>
                            </div>
                            <!-- End of Step -->
                          </div>
                        </div>

                        <div class="row">
                          <div style="height: 150px;"></div>
                        </div>
                      </div>
                    </div>

                    <div class="login-footer"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        <div class="row">
          <div style="height: 150px;"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<!-- END: Content-->
<script>
// import 'vuejs-noty/dist/vuejs-noty.css'
export default {
  name: 'Home',
  middleware: ['guest'],
  mounted() {
    // this.$noty.success("Your profile has been saved!")
  }
}
</script>

  <style lang="css" scoped>

  /* .card-overlay {
    position: relative;
  } */
  .flexbox-container {
    margin-top: -250px;
  }

.card-overlay img {
    transform-origin: 0% 50%;
  transform: skewY(-3deg);
  height:550px;
  width:  100%;
}


  </style>

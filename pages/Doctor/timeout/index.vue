<template>
  <div>
    <body class="vertical-layout 2-columns navbar-floating footer-static pace-done menu-hide" data-open="click" data-menu="vertical-menu-modern" data-col="2-columns" style="overflow: auto;">
      <Header></Header>
      <Sidebar></Sidebar>

      <div class="app-content content">
        <div class="content-overlay"></div>
        <div class="header-navbar-shadow"></div>
        <div class="content-wrapper">
          <div class="content-header row justify-content-center">
            <div class="content-header-left col-md-5 col-12 mb-2">
              <div class="row breadcrumbs-top">
                <div class="col-12">
                  <h4 class="content-header-title float-left mb-0">
                    Expired
                  </h4>
                </div>
              </div>
            </div>
          
          </div>
          <div class="content-body">
            <section class="page-users-view">
              <div class="row justify-content-center">
                <!-- account start -->
                <div class="col-12 col-md-5 col-lg-5">
                  <div class="card justify-content-center">
                    <div class="card-body">
                      <div class="row">
                        <div class="col-12 col-sm-12 col-md-12 col-lg-12">
                          <small>Sorry this session has expired.</small>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
          </div>
        </div>
      </div>
      <!-- END: Content-->

      <div class="sidenav-overlay"></div>
      <div class="drag-target"></div>

      <Footer></Footer>
    </body>
  </div>
</template>
<script>
import Header from '~/components/doctor/header'
import Footer from '~/components/doctor/footer'
import Sidebar from '~/components/doctor/sidebar'

export default {
  name: 'Timeout',
  components: {
    Header,
    Footer,
    Sidebar
  },
  middleware:['auth','doctor']
}
</script>


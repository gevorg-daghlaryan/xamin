<template>
  <div class="text-left iq-breadcrumb-one black breadcrumb">
    <div class="container">
      <div class="row align-items-center">
          <div class="col-lg-6 col-md-8 text-left align-self-center">
              <nav aria-label="breadcrumb" class="text-left">
                  <h2 class="title">Contact Us</h2>
                  <ol class="breadcrumb main-bg">
                      <li class="breadcrumb-item"><a href="/landing-page-1">Home</a></li>
                      <li class="breadcrumb-item active">Contact Us</li>
                  </ol>
              </nav>
          </div>
          <div class="col-lg-6 col-md-4 col-sm-12 text-right wow fadeInRight"> <img alt="banner" class="img-fluid float-right" :src="require('../../assets/images/about-us/image-4.png')"></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name:'BreadCrump'
}
</script>
<style>
  .breadcrumb {
    background-image: url("../../assets/images/contact-us/contuct-us.png");
    background-repeat: no-repeat;
    padding: 90px 0px 0px;
  }
</style>

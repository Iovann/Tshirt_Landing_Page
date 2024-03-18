<template>
  <div>
    <div class="container-fluid alert mb-0 p-0 " id="pub" style="background-color: rgba(180, 121, 217, 0.2);">
            <div class="row align-items-center w-100">
                <div class="col-7 d-flex justify-content-end ">
                    <span class="ms-3 fw-semibold align-self-center "> Free shipping on all U.S. orders $50+</span>
                </div>
                <div class="col-5 d-flex justify-content-end px-0">
                    <img src="../assets/icons/croix.svg" alt="" @click="close=true"  class="btn p-0 ps-2" id="croix">
                </div>
            </div>
        </div>

    <nav class="navbar navbar-expand-lg bg-body-tertiary d-none d-lg-flex py-0 ">
            <div class="d-none d-lg-block">
                <navtext/>
            </div>
            <div class="container-fluid  d-flex d-xxl-none  justify-content-lg-center">
                <a class="navbar-brand" href="#"><img src="../assets/images/logo-black.png.svg" alt=""></a>  
            </div>
            <div class="container-fluid  d-none d-xxl-flex  justify-content-xxl-end w-50 me-5 pe-5">
                <a class="navbar-brand me-5" href="#"><img src="../assets/images/logo-black.png.svg" alt=""></a>  
            </div>
            <div class="d-lg-flex container-fluid w-50 mx-0 justify-content-end d-none pe-3">
                    <img src="../assets/our team/search.svg" alt="" class="me-3 mt-2 ">
                    <img src="../assets/our team/account.svg" alt="" class="me-3 mt-2">
                    <button type="button" class="btn position-relative rounded-circle me-3 " style="background-color: #F3F3F3;">
                        <img src="../assets/our team/étoile.svg" alt="">
                        <span class="position-absolute top-0 start-100 translate-middle bg-success border border-light rounded-circle">
                            <span class="badge text-white">0</span>
                        </span>
                    </button>
                    <button type="button" class="btn position-relative rounded-circle" style="background-color: #F3F3F3;">
                        <img src="../assets/icons/shop.svg" alt="">
                        <span class="position-absolute top-0 start-100 translate-middle bg-success border border-light rounded-circle">
                            <span class="badge text-white">0</span>
                        </span>
                    </button>
                    <div class="ms-5">
                        <button class="btn btn-light shadow-sm btn-lg d-none d-xxl-inline ">Let's Talk</button>
                    </div>
            </div>
        </nav>
        <!-- navbar --md -->
        <nav class="navbar navbar-expand-lg bg-body-tertiary d-flex d-lg-none py-0 ">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="../assets/images/logo-black.png.svg" alt="">
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#Dropdown" aria-controls="Dropdown" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-center" id="Dropdown">
                    <navtext/>
                </div>
            </div>
        </nav>
  </div>
</template>

<script>
import navtext from '../components/Home1/navtext.vue'
export default {
    name : 'navigationBar',

    components:
    {
        navtext,
       
    },
}
</script>

<style>

</style>
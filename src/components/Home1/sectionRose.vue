<template>
      <div class="container-fluid p-0 zone-rose" id="zone-rose" style="max-width: 97%;">
        <div class="row justify-content-center justify-content-xl-between" style="background-color: rgba(180, 121, 217, 0.15);">
            <div class="col-md-3 ps-0 d-none d-lg-block">
                <img src="../../assets/images/believe.svg" alt="" >
                <div class="">
                    <img src="../../assets/images/two.svg" alt="">
                    <img src="../../assets/images/dame.svg" alt="" class="d-none d-xl-inline">
                </div>
            </div>
            <div class="col-lg-6 align-self-center ">
                <div class="row justify-content-center lh-lg fw-bold display-5 ">
                    <p class="col-lg-9 text-center ">
                        Enjoy up your vacations in the best T-shirts
                    </p>
                </div>
                <p class="text-center mb-3 fw-lighter">T-shirts that keep you moving.</p>
                <p class="text-center">
                    <span class="btn btn-success py-3 rounded-4 me-2">Shop Now<img src="../../assets/icons/arrow_white.svg" alt="" class="ps-2"></span>
                    <span class="btn btn-light fw-semibold py-3 rounded-4 mS-2">Contact Us<img src="../../assets/icons/arrow black.svg" alt="" class="ps-2"></span>
                </p>
            </div>
            <div class="col-md-3 pe-0 d-none d-xl-block">
                <p><img src="../../assets/images/baby_women.svg" alt=""></p>
                <p class=" d-none d-xl-block text-end"><img src="../../assets/images/dame_1.svg" alt="" class="100"></p>
                <p class="d-none d-xl-block "><img src="../../assets/images/feel_good.svg" alt="" class=""></p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'section_rose',
}
</script>

<style>

@media (max-width: 769px) {
    #zone-rose
    {
        width: 93%;
    }
}
</style>
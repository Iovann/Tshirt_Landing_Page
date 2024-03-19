<template>
    <section>
        <navigationBar/>
        <section class="py-2" id="service">
          <div class="container-fluid  " style="background-color: #F3F3F3;">
              <div class="container py-1 ">
                  <nav style="--bs-breadcrumb-divider: '>';" aria-label="breadcrumb">
                      <ol class="breadcrumb justify-content-center mb-0 text-center">
                          <li class="breadcrumb-item"><a href="#" class="text-decoration-underline fw-bolder link-offset-3-hover">Home</a></li>
                          <li class="breadcrumb-item active fw-bold " aria-current="page">About US</li>
                      </ol>
                  </nav>
              </div>
          </div>
      </section>

      <section class="container">
        <div class="row">
            <div class="col-lg-6 pb-5 pt-2 py-lg-0 text-center text-lg-start">
                <span class="btn rounded-pill" style="color: purple; background-color: rgba(180, 121, 217, 0.15);">Design your own</span> <br>
                
                <div class="row pb-3 justify-content-lg-between justify-content-center   text-lg-start text-center">
                    <div class="col-lg-8 py-3 ">
                        <p class="h2">Create stunning print for your business</p>
                        <p class="fw-lighter">
                            T-shirt Printing for Everyone. Get a headstart with free design
                            templates you can customize in a few clicks.
                        </p>
                    </div>
                    <div class="col-lg-9 col-10 text-start ">
                        <p class="align-items-center fw-semibold"> <img src="../assets/service détail/check.svg" alt="" class="px-1 py-2 me-2 rounded-circle" style="background-color: rgba(17, 177, 150, 0.15);"> Top quality prints using the latest technology </p>
                        <p class="align-items-center fw-semibold"> <img src="../assets/service détail/check.svg" alt="" class="px-1 py-2 me-2 rounded-circle" style="background-color: rgba(17, 177, 150, 0.15);"> Mix and match colors, sizes, and designs </p>
                        <p class="align-items-center fw-semibold"> <img src="../assets/service détail/check.svg" alt="" class="px-1 py-2 me-2 rounded-circle" style="background-color: rgba(17, 177, 150, 0.15);">Fast and free standard shipping</p>
                        <p class="align-items-center fw-semibold"> <img src="../assets/service détail/check.svg" alt="" class="px-1 py-2 me-2 rounded-circle" style="background-color: rgba(17, 177, 150, 0.15);"> Customer happiness guarantee </p>
                    </div>
                </div>
                <button class="btn text-white btn-lg px-3" style="background-color: #2EBB77;">Custom T-shirt</button>
            </div>

            <div class="col-lg-5">
                <img src="../assets/about/hero.svg" alt="" class="img-fluid">
            </div>
        </div>
      </section>

      <section class="container py-5 ">
                
            <p class="text-center"><span class="btn rounded-pill" style="color: purple; background-color: rgba(180, 121, 217, 0.15);">Fast and Quality Service</span> <br></p>
            <div class="col-12 pb-4">
                <div class="row justify-content-center">
                    <p class="col-lg-5 col-8 text-center h2 fw-bold">
                        T-shirt printing made easy.
                    </p>
                </div>
            </div>
        <div class="row justify-content-between">
                <div class="col-lg-6 mb-5 mb-lg-0">
                    <img src="../assets/service/energy_pos.svg" alt="" class="img-fluid">
                </div>

                <div class="col-lg-5">
                    <div class="accordion accordion-flush " id="accordionFlushExample">
                        <div class="accordion-item mb-4">
                            <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne" @click="isButtonClicked = true">
                                <span class="fw-semibold">Graphic Design Services</span>
                            </button>
                            </h2>
                            <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                                <div class="accordion-body">
                                    To make a T-shirt design, your first need to install specific graphic
                                    design software. Once you’ve done that, start your creation and make
                                    sure that your final design is at least 220 PPI so it won’t be pixelated
                                    when printed…
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item mb-4">
                            <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                                <span class="fw-semibold">Printing Services</span>
                            </button>
                            </h2>
                            <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                                <div class="accordion-body">
                                    To make a T-shirt design, your first need to install specific graphic
                                    design software. Once you’ve done that, start your creation and make
                                    sure that your final design is at least 220 PPI so it won’t be pixelated
                                    when printed…
                                </div>                        
                            </div>
                        </div>
                        <div class="accordion-item mb-4">
                            <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                                <span class="fw-semibold">POD for online stores</span>
                            </button>
                            </h2>
                            <div id="flush-collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                                <div class="accordion-body">
                                    To make a T-shirt design, your first need to install specific graphic
                                    design software. Once you’ve done that, start your creation and make
                                    sure that your final design is at least 220 PPI so it won’t be pixelated
                                    when printed…
                                </div>                       
                            </div>
                        </div>

                        <div class="accordion-item mb-4">
                            <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapsefour" aria-expanded="false" aria-controls="flush-collapseThree">
                                <span class="fw-semibold">Branding & white-label printing</span> 
                            </button>
                            </h2>
                            <div id="flush-collapsefour" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                                <div class="accordion-body">
                                    To make a T-shirt design, your first need to install specific graphic
                                    design software. Once you’ve done that, start your creation and make
                                    sure that your final design is at least 220 PPI so it won’t be pixelated
                                    when printed…
                                </div>                       
                            </div>
                        </div>
                    </div>
                </div>
            </div>
      </section>

      <section class="container">
        <p class="text-center"><span class="btn rounded-pill" style="color: purple; background-color: rgba(180, 121, 217, 0.15);">Join us Today</span> <br></p>
            <div class="col-12 pb-4">
                <div class="row justify-content-center">
                    <p class="col-lg-5 col-8 text-center h2 fw-bold">
                        Meet our team!
                    </p>
                </div>
            </div>

            <div class="row py-4 justify-content-center   justify-content-md-between">
                    <div class="col-md-6 col-lg-3 col-8 col-sm-6 card px-2 border-0 mb-3">
                        <div class="rounded-4 border border-1 bg-white">
                            <img src="../assets/our team/Arlene3.svg" class="img-fluid rounded-top-4 card-img-top" alt="...">
                            <div class="card-body text-center">
                                <h5 class="card-title">Arlene McCoy</h5>
                                <p class="card-text fw-lighter ">President of Sales</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 col-8 col-sm-6 card px-2 border-0 mb-3">
                        <div class="rounded-4 border border-1 bg-white">
                            <img src="../assets/our team/Mary_Lous.svg" class="img-fluid rounded-top-4 card-img-top" alt="...">
                            <div class="card-body text-center">
                                <h5 class="card-title">Mary Lous</h5>
                                <p class="card-text fw-lighter ">Copy Writer</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 col-8 col-sm-6 card px-2 border-0 mb-3">
                        <div class="rounded-4 border border-1 bg-white">
                            <img src="../assets/our team/Marilin.svg" class="img-fluid rounded-top-4 card-img-top" alt="...">
                            <div class="card-body text-center">
                                <h5 class="card-title">Marilin</h5>
                                <p class="card-text fw-lighter">Designer</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 col-8 col-sm-6 card px-2 border-0 mb-3">
                        <div class="rounded-4 border border-1 bg-white">
                            <img src="../assets/our team/Cristina.svg" class="img-fluid rounded-top-4 card-img-top" alt="...">
                            <div class="card-body text-center">
                                <h5 class="card-title">Cristina</h5>
                                <p class="card-text fw-lighter ">Director</p>
                            </div>
                        </div>
                    </div>
                </div>

        <p class="text-center py-5">
            <button class="btn btn-light btn-lg px-2 py-1 shadow-sm fs-6 border border-1 border-black">Join Our Team</button>
        </p>
    </section>

    <section class="container-fluid" style="background-color: #f7f7f7;">
           <div class="container py-5">
               <div class="row  justify-content-between">
                   <div class="col-lg-4 mt-5">
                        <div class="row align-items-center mt-lg-5 ">
                            <div class="col-12 col-lg-5 text-center d-none d-lg-block">
                                <img src="../assets/about/téléchargement (1).png" alt="" class="rounded-circle img-fluid py-2 bg-white w-75 float-end ">
                            </div>
                            <div class="col-lg-6 d-flex d-lg-block  text-center justify-content-center ">
                                <p class="pb-lg-5"><img src="../assets/about/logo_vert.svg" alt="" class="img-fluid w-50  ms-lg-5 logo"></p>
                                <p class="pt-lg-5"><img src="../assets/about/logo_window.svg" alt="" class="img-fluid w-50 logo"></p>
                            </div>
                        </div>
                   </div>   
                   
                   <div class="col-lg-4 text-center">
                        <p class="">
                            <img src="../assets/about/logo_bleu.svg" alt="" class="img-fluid logo1" style="width: 40%;">
                        </p>

                        <p class="h2 fw-bold "> Join the 7,000+  companies trusting us</p>
                        <p class="fw-lighter"> You’ve got the ideas, we’ve got the tools</p>
                        <button class="btn btn-lg px-2 text-white fw-bold " style="background-color: #2EBB77;">Get Started</button>
                   </div>

                   <div class="col-lg-4 mt-3 mt-lg-0">
                        <div class="row align-items-center justify-content-center ">
                            <div class="col-lg-5 mt-lg-5 text-center d-flex d-lg-block  justify-content-center justify-content-lg-start  ">
                                <p class="pb-lg-5"><img src="../assets/about/logo_violet.svg" alt="" class="img-fluid  align-self-start mt-lg-5 mt-2 w-50 logo2"></p>
                                <p class="pt-lg-5"><img src="../assets/about/logo_s_vert.svg" alt="" class="img-fluid align-self-end ms-lg-5 w-75 logo"></p>
                            </div>
                            <div class="col-sm-2 d-none d-lg-block me-5 col-lg-5">
                                <img src="../assets/about/téléchargement (1).png" alt="" class="rounded-circle img-fluid py-2 bg-white w-75 float-end">
                            </div>
                        </div>
                   </div>
               </div>
           </div>
    </section>

    <section class="container py-5 ">
        <p class="text-center"><span class="btn rounded-pill" style="color: purple; background-color: rgba(180, 121, 217, 0.15);">Testimonials</span> <br></p>
        <p class="h1 text-center py-3">What People Are Saying</p>
        <div class="row justify-content-evenly">
            <div class="card col-10 col-md-8 my-3 my-lg-0 col-lg-3 p-4 border-0 text-center rounded-4 shadow-lg">
                <div class="row">
                    <div class="col-4">
                        <img src="../assets/images/dean.svg" alt="" >
                    </div>
                    <div class="col-7 align-self-end ">
                        <p class="fw-lighter"><span class="fw-bold">Dean D.</span> Director</p>
                    </div>
                </div>
                <div class="row">
                    <p class="fw-semibold">
                        “ Great quality products - Flags,
                        programs for exceptional capacities,
                        birthday, and occasion welcome are
                        largely still mainstream on paper.”
                    </p>
                </div>
            </div>

            <div class="card col-10 col-md-8 my-3 my-lg-0 col-lg-3 p-4 border-0 text-center rounded-4 shadow-lg">
                <div class="row">
                    <div class="col-4">
                        <img src="../assets/images/christian.svg" alt="" >
                    </div>
                    <div class="col-7 align-self-end ">
                        <p class="fw-lighter"><span class="fw-bold">Cristian L.</span> Manager</p>
                    </div>
                </div>
                <div class="row">
                    <p class="fw-semibold">
                        “ Best services ever - Flags, programs
                        for exceptional capacities, birthday,
                        and are largely still mainstream on
                        paper occasion welcome.”
                    </p>
                </div>
            </div>

            <div class="card col-10 col-md-8 my-3 my-lg-0 col-lg-3 p-4 border-0 text-center rounded-4 shadow-lg">
                <div class="row">
                    <div class="col-4">
                        <img src="../assets/images/leonel.svg" alt="" >
                    </div>
                    <div class="col-7 align-self-end ">
                        <p class="fw-lighter"><span class="fw-bold">Lionel R.</span> Designer</p>
                    </div>
                </div>
                <div class="row">
                    <p class="fw-semibold">
                        “ Top noth support - Flags, programs
                        for, birthday, and occasion welcome
                        are largely still mainstream on paper
                        exceptional capacities.”
                    </p>
                </div>
            </div>
        </div>
    
    </section>

    <section class="container-fluid" id="banner">
        <div class="container text-center text-lg-start " >
            <div class="row justify-content-lg-between justify-content-center  align-items-center">
                <div class="col-lg-6 p-5 " id="bannerfirstpart">
                    <p class="h1 fw-bold ">Enjoy up your vacations in the best T-shirts</p>
                    <p>T-shirts that keep you moving.</p>

                    <div class="row justify-content-center justify-content-md-start">
                        <div class="col-md-6">
                            <button class="btn btn-light rounded-3 fw-bold px-4 py-3 ">Shop Now <img src="../assets/service détail/black_arrow.svg" class="ms-2" alt=""></button>
                        </div>
                        <div class="col-md-6 mt-4 mt-md-0">
                            <button class="btn btn-light rounded-3 fw-bold px-4 py-3 ">Contact Us <img src="../assets/service détail/black_arrow.svg" class="ms-2" alt=""></button>
                        </div>
                    </div>
                </div>
                <div class="col-lg-5" id="bannersecondpart py-4">
                    <img src="../assets/service détail/banniere_verte.svg" alt="" class="img-fluid">
                </div>
            </div>
        </div>
    </section>
        <secondfooter/>
</section>
</template>

<script>
import navigationBar from "../components/navbar.vue";
import secondfooter from "../components/secondfooter.vue"
export default {
    name: 'AboutVue',
    components: {
        navigationBar,
        secondfooter,
    },

    data() {
    return {
      isButtonClicked: false,
    }
  },
}
</script>

<style>
#banner{
    background-color: rgba(100, 203, 154, 0.9);
    background-image: url(../assets/grand_cercle.svg);
    background-repeat: no-repeat;
    background-position:bottom left -8% ;
}
#bannerfirstpart{
    background-image: url(../assets/pricing/petit_cercle.svg);
    background-repeat: no-repeat;
    background-position: right  top 0%;
}

@media (max-width:992px) {
    
    img.logo{
        width:45% !important;
    }

    img.logo1{
        width: 20% !important;
    }
}
</style>
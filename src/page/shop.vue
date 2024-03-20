<template>
  <section>
    <navigationBar/>
    <section class="py-5" id="service">
            <div class="container-fluid p-5 " style="background-color: #F3F3F3;">
                <div class="container">
                    <p class="h1 text-center">Shop</p>
                    <nav style="--bs-breadcrumb-divider: '>';" aria-label="breadcrumb">
                        <ol class="breadcrumb justify-content-center">
                            <li class="breadcrumb-item"><a href="#" class="text-decoration-underline fw-bolder link-offset-3-hover">Home</a></li>
                            <li class="breadcrumb-item active" aria-current="page">Shop</li>
                        </ol>
                    </nav>
                </div>
            </div>
        </section>

        <p class="text-center">
          <button class="btn btn-primary d-inline d-lg-none" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample" aria-controls="offcanvasExample">
              Aside
          </button>
      </p>

      <div class="offcanvas offcanvas-start  d-lg-none" tabindex="-1" id="offcanvasExample" aria-labelledby="offcanvasExampleLabel">
          <div class="offcanvas-header">
              <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
          </div>
          <div class="offcanvas-body">
              <h2 class="fw-bold">Search</h2>
                  <div class="d-flex position-relative ">
                      <input type="text" class="form-control position-relative" placeholder="Search...">
                      <button class="btn border-0 " id="loupe" type="submit">
                          <img src="../assets/blog/search.svg" alt="">
                      </button>
                  </div>
                  <h2 class="fw-bold pb-3 pt-5">Product categories</h2>
                  <div class="row py-3 ">
                      <div class="col-12 mb-3  d-flex justify-content-between">
                          <span class="fw-lighter">Hoodie</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Kids</span>
                          <span class="fw-bold">4</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Long Sleeves</span>
                          <span class="fw-bold">0</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Product Designer</span>
                          <span class="fw-bold">2</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Sweater</span>
                          <span class="fw-bold">2</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">T-Shirt</span>
                          <span class="fw-bold">5</span>
                      </div>
                  </div>
                  <h2 class="fw-bold pb-3 pt-3">Filter by price</h2>
                 
                  <input type="range" class="form-range" min="10" max="160" step="5" v-model="rangeValue">
                  
                    <div class="d-flex justify-content-between align-items-center">
                      <span class="fw-bolder">PRICE : ${{ rangeValue }}</span>
                      <button class="btn text-dark fw-bold " style="background-color: #F3F3F3;">FILTER</button>
                    </div>
                  <h2 class="fw-bold pb-3 pt-5">Filter by Color</h2>
                  
                  <div class="row py-3 ">
                      <div class="col-12 mb-3  d-flex justify-content-between">
                          <span class="fw-lighter"><img src="../assets/shop/btn_black.svg" alt="" class="me-2"> Black</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter"><img src="../assets/shop/btn_brown.svg" alt="" class="me-2"> Brown</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                        <span class="fw-lighter"><img src="../assets/shop/btn_red.svg" alt="" class="me-2"> Red</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                        <span class="fw-lighter"><img src="../assets/shop/btn_white.svg" alt="" class="me-2"> White</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                        <span class="fw-lighter"><img src="../assets/shop/btn_yellow.svg" alt="" class="me-2"> Yzllow</span>
                          <span class="fw-bold">11</span>
                      </div>
                  </div>

                  <h2 class="fw-bold pb-3 pt-5">Stock status</h2>

                  <form action="">
                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex1" >
                      <label class="form-check-label fw-lighter " for="flex1"> On sale</label>
                    </div>

                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex2" >
                      <label class="form-check-label fw-lighter " for="flex2">  In stock</label>
                    </div>

                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex2" >
                      <label class="form-check-label fw-lighter " for="flex2">  Out of stock</label>
                    </div>

                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex2" >
                      <label class="form-check-label fw-lighter " for="flex2">   On back order</label>
                    </div>

                  </form>

                  <h2 class="fw-bold pb-3 pt-5">Product tags</h2>

                  <div class="row">
                    <div class="col-12 d-flex  align-items-center">
                      <span class="px-2 pt-1  me-3  rounded-2 " style="background-color: #F3F3F3;">Designer</span>
                      <span class="px-2 pt-1  me-3  rounded-2 " style="background-color: #F3F3F3;">Kids</span>
                      <span class="px-2 pt-1  me-3  rounded-2 " style="background-color: #F3F3F3;">T-shirt</span>
                    </div>
                    <div class="col-4 mt-3 ">
                      <span class="p-2 rounded-2 " style="background-color: #F3F3F3;">Woman</span>
                    </div>
                  </div>

          </div>
      </div>

    <section class="container">
      <div class="row">
        <div class="col-3 pb-5 d-none d-lg-block ">
          <h2 class="fw-bold">Search</h2>
          <div class="d-flex position-relative ">
              <input type="text" class="form-control position-relative" placeholder="Search...">
                      <button class="btn border-0 " id="loupe" type="submit">
                  <img src="../assets/blog/search.svg" alt="">
              </button>
          </div>
          <h2 class="fw-bold pb-3 pt-5">Product categories</h2>
                  <div class="row py-3 ">
                      <div class="col-12 mb-3  d-flex justify-content-between">
                          <span class="fw-lighter">Hoodie</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Kids</span>
                          <span class="fw-bold">4</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Long Sleeves</span>
                          <span class="fw-bold">0</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Product Designer</span>
                          <span class="fw-bold">2</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Sweater</span>
                          <span class="fw-bold">2</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">T-Shirt</span>
                          <span class="fw-bold">5</span>
                      </div>
                  </div>
                  <h2 class="fw-bold pb-3 pt-3">Filter by price</h2>
                 
                  <input type="range" class="form-range" min="10" max="160" step="5" v-model="rangeValue">
                  
                    <div class="d-flex justify-content-between align-items-center">
                      <span class="fw-bolder">PRICE : ${{ rangeValue }}</span>
                      <button class="btn text-dark fw-bold " style="background-color: #F3F3F3;">FILTER</button>
                    </div>
                  <h2 class="fw-bold pb-3 pt-5">Filter by Color</h2>
                  
                  <div class="row py-3 ">
                      <div class="col-12 mb-3  d-flex justify-content-between">
                          <span class="fw-lighter"><img src="../assets/shop/btn_black.svg" alt="" class="me-2"> Black</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter"><img src="../assets/shop/btn_brown.svg" alt="" class="me-2"> Brown</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                        <span class="fw-lighter"><img src="../assets/shop/btn_red.svg" alt="" class="me-2"> Red</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                        <span class="fw-lighter"><img src="../assets/shop/btn_white.svg" alt="" class="me-2"> White</span>
                          <span class="fw-bold">11</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                        <span class="fw-lighter"><img src="../assets/shop/btn_yellow.svg" alt="" class="me-2"> Yzllow</span>
                          <span class="fw-bold">11</span>
                      </div>
                  </div>

                  <h2 class="fw-bold pb-3 pt-5">Stock status</h2>

                  <form action="">
                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex1" >
                      <label class="form-check-label fw-lighter " for="flex1"> On sale</label>
                    </div>

                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex2" >
                      <label class="form-check-label fw-lighter " for="flex2">  In stock</label>
                    </div>

                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex2" >
                      <label class="form-check-label fw-lighter " for="flex2">  Out of stock</label>
                    </div>

                    <div class="form-check mb-2 ">
                      <input class="form-check-input" type="checkbox" value="" id="flex2" >
                      <label class="form-check-label fw-lighter " for="flex2">   On back order</label>
                    </div>

                  </form>

                  <h2 class="fw-bold pb-3 pt-5">Product tags</h2>

                  <div class="row">
                    <div class="col-12 d-flex  align-items-center">
                      <span class="px-2 pt-1  me-3  rounded-2 " style="background-color: #F3F3F3;">Designer</span>
                      <span class="px-2 pt-1  me-3  rounded-2 " style="background-color: #F3F3F3;">Kids</span>
                      <span class="px-2 pt-1  me-3  rounded-2 " style="background-color: #F3F3F3;">T-shirt</span>
                    </div>
                    <div class="col-4 mt-3 ">
                      <span class="p-2 rounded-2 " style="background-color: #F3F3F3;">Woman</span>
                    </div>
                  </div>

          </div>
      </div>
    </section>
        
    <!-- <card_Row/> -->
    <firstfooter/>
  </section>
</template>

<script>
// import
// import card_Row from "../components/card_row.vue"
import navigationBar from "../components/navbar.vue";
import firstfooter from "../components/Home1/footer.vue";
export default {
    name: 'ShopVueCompo',
    components: {
        // card_Row,
        navigationBar,
        firstfooter,
    },

    data() {
    return {
      rangeValue: 0,
    };
  },

    
}
</script>

<style>
#loupe{
  position: absolute;
  left: 89%;
}
</style>
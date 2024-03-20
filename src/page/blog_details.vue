<template>
  <section>
      <navigationBar/>

      <section class="py-5" id="service">
          <div class="container-fluid  " style="background-color: #F3F3F3;">
              <div class="container py-1 ">
                  <nav style="--bs-breadcrumb-divider: '>';" aria-label="breadcrumb">
                      <ol class="breadcrumb justify-content-center mb-0 text-center">
                          <li class="breadcrumb-item"><a href="#" class="text-decoration-underline fw-bolder link-offset-3-hover">Home</a></li>
                          <li class="breadcrumb-item active" aria-current="page">Design Services</li>
                          <li class="breadcrumb-item active fw-semibold" aria-current="page">What make you beautiful with us</li>
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
                  <h2 class="fw-bold pb-3 pt-5">Categories</h2>
                  <div class="row py-3 ">
                      <div class="col-12 mb-3  d-flex justify-content-between">
                          <span class="fw-lighter">Design Services</span>
                          <span class="fw-bold">6</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">HaruTheme</span>
                          <span class="fw-bold">4</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Print Company</span>
                          <span class="fw-bold">3</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Print Shop</span>
                          <span class="fw-bold">3</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Uncategorized</span>
                          <span class="fw-bold">5</span>
                      </div>
                  </div>
                  <h2 class="fw-bold pb-3 pt-3">Latest Posts</h2>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside1.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Design Services</p>
                          <p class="fw-bold">What make you beautiful with us</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside2.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Design Services, HaruTheme</p>
                          <p class="fw-bold">Mirum est notare quem littera gothica</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside3.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Design Services, HaruTheme</p>
                          <p class="fw-bold">Ut wisi enim ad minim veniam</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside4.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">HaruTheme</p>
                          <p class="fw-bold">How to make a T-shirt design online</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside5.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Print Company</p>
                          <p class="fw-bold">Let say it your way</p>
                      </div>                        
                  </div>

                  <div class="d-flex justify-content-center">
                      <img src="../assets/blog/shop_now.svg" alt="" class="img-fluid">
                  </div>

                  <h2 class="fw-bold pb-3 pt-5">Tags</h2>

                  <div class="flex-wrap">
                      <p>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">company</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Design Services</span><br>
                      </p>
                      <p class="flex-wrap">
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">HaruTheme</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Pricom</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Print</span><br>
                      </p>
                      <p class="flex-wrap">
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Printing</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Printshop</span>
                      </p>
                  </div>
          </div>
      </div>

      <section class="container"  id="page_complete">
          <div class="row">
              <div class="col-lg-3 d-none d-lg-block">
                  <h2 class="fw-bold">Search</h2>
                  <div class="d-flex">
                      <input type="text" class="form-control position-relative" placeholder="Search...">
                      <button class="btn border border-star-0" type="submit">
                          <img src="../assets/blog/search.svg" alt="">
                      </button>
                  </div>
                  <h2 class="fw-bold pb-3 pt-5">Categories</h2>
                  <div class="row py-3 ">
                      <div class="col-12 mb-3  d-flex justify-content-between">
                          <span class="fw-lighter">Design Services</span>
                          <span class="fw-bold">6</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">HaruTheme</span>
                          <span class="fw-bold">4</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Print Company</span>
                          <span class="fw-bold">3</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Print Shop</span>
                          <span class="fw-bold">3</span>
                      </div>
                      <div class="col-12 mb-3 d-flex justify-content-between">
                          <span class="fw-lighter">Uncategorized</span>
                          <span class="fw-bold">5</span>
                      </div>
                  </div>
                  <h2 class="fw-bold pb-3 pt-3">Latest Posts</h2>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside1.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Design Services</p>
                          <p class="fw-bold">What make you beautiful with us</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside2.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Design Services, HaruTheme</p>
                          <p class="fw-bold">Mirum est notare quem littera gothica</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside3.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Design Services, HaruTheme</p>
                          <p class="fw-bold">Ut wisi enim ad minim veniam</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside4.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">HaruTheme</p>
                          <p class="fw-bold">How to make a T-shirt design online</p>
                      </div>                        
                  </div>

                  <div class="row align-items-center justify-content-between mb-3">
                      <div class="col-4">
                          <img src="../assets/blog/aside5.svg" alt="" class="img-fluid">
                      </div>
                      <div class="col-8 px-0 ">
                          <p class="fw-lighter mb-0 ">Print Company</p>
                          <p class="fw-bold">Let say it your way</p>
                      </div>                        
                  </div>

                  <div class="d-flex justify-content-center">
                      <img src="../assets/blog/shop_now.svg" alt="" class="img-fluid">
                  </div>

                  <h2 class="fw-bold pb-3 pt-5">Tags</h2>

                  <div class="flex-wrap">
                      <p>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">company</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Design Services</span><br>
                      </p>
                      <p class="flex-wrap">
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">HaruTheme</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Pricom</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Print</span><br>
                      </p>
                      <p class="flex-wrap">
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Printing</span>
                          <span class="fw-lighter rounded-4 p-2" style="background-color: #F3F3F3;">Printshop</span>
                      </p>
                  </div>
              </div>
              <div class="col-lg-9 px-4 pb-5 mb-5">
                  <p class="text-center">
                    <span class="px-2 py-1 rounded-4" style="background-color: #F3F3F3; color:rgba(46, 187, 119, 1);">Design Services</span>
                  </p>
                  <p class="fw-bold h2 text-center">What make you beautiful with us</p>
                  <div class="row fw-lighter text-center justify-content-center ">
                    <p class="col-lg-6 text-lg-end ">August 20, 2022 &nbsp; --- &nbsp; by <span class="fw-bold"> &nbsp; admin</span></p>
                    
                    <p class="col-lg-3 text-lg-start ">
                      <span class="ps-3 align-items-center">
                          <img src="../assets/blog_details/comments.svg" alt="" class="img-fluid">
                          <span class="ps-2 fw-semibold">3 comments</span>
                      </span>
                    </p>  
                  </div>  

                  <img src="../assets/blog_details/hero.svg" alt="" class="img-fluid ">
                  <p class="fw-lighter mt-4">
                    Nullam imperdiet, sem at fringilla lobortis, sem nibh fringilla nibh, idae gravida mi purus sit amet erat. Ut dictum nisi massa.Maecenas id justo
                    rhoncus, volutpat nunc sit amet, facilisiulum scelerisque dictum Maecenas id justo rhoncus, volutpat nunc sit amet, facilisis sem. Vestibulum
                    scelerisque dictsap.
                  </p>
                  <p class="text-center pt-4"><img src="../assets/blog_details/griffe.svg" alt="" class="img-fluid"></p>

                  <div class="row justify-content-center ">
                    <p class="col-lg-9 fw-bold h5 text-center pb-4 ">
                      I think it’s important people see themselves in film, but it’s even more
                      important they see people they maybe don’t know as well.
                    </p>
                  </div>

                  <p class="fw-lighter">
                    Fusce eget malesuada eros. Vivamus eros dolor, auctor aliquet dolor sit amet, euismod imperdiet ex. Nam sed nulla sed massa suscipit feugiat.
                    Mauris et nunc ornare, placerat ex ac, interdum magna. Vestibulum urna massa, hendrerit sed fringilla in, mollis vitae tellus. Vestibulum mattis nulla
                    elementum tristique fringilla. Morbi in sollicitudin erat. Ut quis tristique mauris. Proin risus purus, iaculis a orci ut, cursus bibendum panisl. Duis
                    aliquam gravida eros eget molestie. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Suspendisse
                    pharetra, arcu eu porta aliquet, eros dui tincidunt purus, eu vehicula magna nisl in purus.
                  </p>

                  <p class="fw-lighter">
                    Vivamus eros dolor, auctor aliquet dolor sit amet, euismod imperdiet ex. Nam sed nulla sed massa suscipit feugiat. Mauris et nunc ornare, placerat
                    ex ac, interdum magna. Vestibulum urna massa, hemolli
                  </p>

                  <div class="row justify-content-between pt-5 text-center">
                      <div class="col-lg-5 fw-lighter d-flex flex-wrap justify-content-center">  <span class="">#company</span>
                        <span class="ms-2">#printing</span>
                        <span class="ms-2">#printshop</span>
                      </div>

                      <div class="col mt-3 mt-lg-0">  <div class="row justify-content-center">  
                        <div class="col-auto fw-bold">Share:</div>  
                          <div class="col-auto mx-2"> 
                            <span class="px-2 border border-1 py-2 shadow-lg rounded-circle">
                              <img src="../assets/blog_details/facebook.svg" alt="" class="p-1">
                            </span>
                          </div>

                            <div class="col-auto mx-2">  
                              <span class="px-2 border border-1 py-2 shadow-lg rounded-circle">
                                <img src="../assets/blog_details/twitter.svg" alt="">
                              </span>
                            </div>

                            <div class="col-auto mx-2">  
                              <span class="px-2 border border-1 py-2 shadow-lg rounded-circle">
                                <img src="../assets/blog_details/linkded.svg" alt="" class="p-1">
                              </span>
                            </div>

                            <div class="col-auto mx-2">  
                              <span class="px-2 border border-1 py-2 shadow-lg rounded-circle">
                                <img src="../assets/blog_details/pinterest.svg" alt="">
                              </span>
                            </div>

                            <div class="col-auto mx-2">  
                              <span class="px-2 border border-1 py-2 shadow-lg rounded-circle">
                                <img src="../assets/blog_details/telegram.svg" alt="">
                              </span>
                            </div>
                        </div>
                    </div>
                  </div>
                  <hr>
                  <div class="align-items-center d-flex ">
                    <p><img src="../assets/blog_details/previous.svg" alt=""></p>
                    <p class="ms-3 ">
                      <span class="text-uppercase fw-lighter ">Previous</span><br>
                      <span class="fw-bold">Post Gallery</span>
                    </p>
                  </div>
                  <hr>

                  <div class="row align-items-center pb-5">
                    <div class="col-lg-2 text-center  text-lg-start ">
                      <img src="../assets/blog_details/avatar.svg" alt="" class="img-fluid">
                    </div>

                    <div class="col-lg-10 text-center text-lg-start ">
                      <p class="fw-bold mb-2 ">admin</p>
                      <p class="fw-lighter mb-2 ">Suspe ndisse suscipit sagittis leo sit met condimentum essum consecte uspe ndisse suscipit sagittis. Suscipit sagittis leo sit met condimentum</p>
                      <span class="text-decoration-underline">Website</span>
                    </div>
                  </div>

                  <p class="h2 text-center fw-bold py-5">You may also like this</p>

                  <div class="row">
                    <div class="col-lg-6 px-2 text-center text-lg-start ">
                      <img src="../assets/blog_details/also1.svg" alt="" class="img-fluid">
                      <p class="text-center py-2 ">
                        <span class="px-2 py-1 rounded-4" style="background-color: #F3F3F3; color:rgba(46, 187, 119, 1);">Design Services</span>
                        <span class="px-2 py-1 rounded-4 ms-3" style="background-color: #F3F3F3; color:rgba(46, 187, 119, 1);">HaruTheme</span>
                      </p>
                      <p class="fw-bold text-center ">10 Steps to Writing the Perfect Prospectus</p>
                    </div>

                    <div class="col-lg-6 px-2 text-center text-lg-start ">
                      <img src="../assets/blog_details/also2.svg" alt="" class="img-fluid">
                      <p class="text-center py-2 ">
                        <span class="px-2 py-1 rounded-4" style="background-color: #F3F3F3; color:rgba(46, 187, 119, 1);">Design Services</span>
                      </p>
                      <p class="fw-bold text-center ">Watch the Sony a9 Livestream Event Online</p>
                    </div>
                  </div>
                  <hr>

                  <p class="text-center fw-bold h3 pt-5 ">There are 3 comments</p>

                  <div class="row align-items-center pb-5 text-center text-lg-start">
                    <div class="col-lg-2 text-center  text-lg-start ">
                      <img src="../assets/blog_details/avatar.svg" alt="" class="img-fluid">
                    </div>

                    <div class="col-lg-10">
                      <p class="fw-bold mb-2 ">Admin</p>
                      <p class="fw-lighter mb-2 ">Nullam imperdiet, sem at fringilla lobortis, sem nibh fringilla nibh, idae gravida mi purus sit amet erat. Ut dictum nisi massa, vitae pusem at fringilla lobor Haruheme</p>
                      
                      <p class="fw-lighter">July 14, 2017 &nbsp;| <span class="fw-bold ms-3">Reply</span></p>
                    </div>
                  </div>


                  <div class="row align-items-center pb-5 text-center text-lg-start">
                    <div class="col-lg-2 text-center  text-lg-start ">
                      <img src="../assets/blog_details/avatar.svg" alt="" class="img-fluid">
                    </div>

                    <div class="col-lg-10">
                      <p class="fw-bold mb-2 ">Admin</p>
                      <p class="fw-lighter mb-2 ">Nullam imperdiet, sem at fringilla lobortis, sem nibh fringilla nibh, idae gravida mi purus sit amet erat. Ut dictum nisi massa, vitae pusem at fringilla lobor Haruheme</p>
                      <p class="fw-lighter">July 22, 2022 &nbsp;| <span class="fw-bold ms-3">Reply</span></p>
                    </div>
                  </div>

                  <div class="row align-items-center pb-5 ms-lg-5 text-center text-lg-start">
                    <div class="col-lg-2 text-center  text-lg-start ">
                      <img src="../assets/blog_details/avatar.svg" alt="" class="img-fluid">
                    </div>

                    <div class="col-lg-10">
                      <p class="fw-bold mb-2 ">Admin</p>
                      <p class="fw-lighter mb-2 ">Nullam imperdiet, sem at fringilla lobortis, sem nibh fringilla nibh, idae gravida mi purus sit amet erat. Ut dictum nisi massa, vitae pusem at fringilla lobor Haruheme</p>
                      <p class="fw-lighter">July 14, 2017 &nbsp;| <span class="fw-bold ms-3">Reply</span></p>
                    </div>
                  </div>

                  <p class="text-center fw-bold h3 pt-5 py-5 text-center ">Leave us a comment</p>

                  <form action="">
                    <div class="row mb-4">
                      <div class="col">
                        <input type="text" class="form-control" placeholder="Enter Your Name*" required style="background-color: #F3F3F3;">
                      </div>
                      <div class="col">
                        <input type="email" class="form-control" placeholder="Enter Your Email*" required style="background-color: #F3F3F3;">
                      </div>
                    </div>
                    <textarea name="message" class="form-control" id="" rows="5" style="background-color: #F3F3F3;"></textarea>

                    <div class="form-check justify-content-center d-flex py-5">
                      <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
                      <label class="form-check-label ms-2 fw-lighter" for="flexCheckDefault">
                        Save my name, email, and website in this browser for the next time I comment.
                      </label>
                    </div>

                    <p class="text-center"><button type="submit" class="btn btn-lg text-white fw-semibold " style="background-color: rgba(46, 187, 119, 1);">Post Comment</button></p>
                  </form>
              </div>
          </div>
      </section>
      <firstfooter/>
  </section>
</template>
<script>
import navigationBar from "../components/navbar.vue";
import firstfooter from "../components/Home1/footer.vue";
export default {
    name: 'blog_détail',
    components: {
        navigationBar,
        firstfooter,
    },
}
</script>

<style>
#loupe{
  position: absolute;
  left: 89%;
}
</style>
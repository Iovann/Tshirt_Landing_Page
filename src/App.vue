<template>
  <div id="App">
    <AboutVue/>
    <!-- <blog_details/> -->
    <!--<blog/>-->
    <!-- <faq/> -->
    <!-- <pricing_plan/> -->
    <!-- <HomeCompo/> -->
    <!-- <our_team/> -->
    <!-- <ServicePage/> -->
    <!-- <service_detail/> -->

  </div>
</template>

<script>
import AboutVue from './page/About.vue';
// import blog_details from './page/blog_details.vue'
// import blog from './page/Blog.vue';
// import faq from './page/FAQ.vue';
// import pricing_plan from "./page/pricing.vue";
// import service_detail from './page/service_détail.vue'
// import HomeCompo from "./page/home.vue";
// import our_team from "./page/Ourteam.vue"
// import ServicePage from "./page/Service.vue"
export default {
  name: 'App',
  components: {
    AboutVue,
    // blog_details,
    // blog,
    // faq,
    // HomeCompo,
    // our_team,
    // ServicePage,
    // service_detail,
    // pricing_plan,
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap");
#App
{
  font-family: "Plus Jakarta Sans";
}
</style>

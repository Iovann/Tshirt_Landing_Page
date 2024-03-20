<template>
  <div class="card col-lg-4 col-md-6 position-relative border-0">
        <img :src="card.image" class="rounded-3" alt="...">
        <div class="card-body">
            <span class="position-absolute top-0 ">
                <span class="btn btn-success text-white py-2 px-3 mt-3">!Sale</span><br>
                <span class="btn text-white py-2 px-3 mt-1" style="background-color: rgb(180, 121, 217); margin-top: 18%;"> New</span>
            </span>
                    
            <p class="text-center fw-bold mt-3 card-title">Youth Short Sleeve Tee</p>
            <p class="text-center">
                        <span class="fw-bold">${{ card.price }}</span>
            </p>
            <p class="text-center align-items-center ">
                <span class=""> <img src="../assets/icons/point noir.svg" alt=""></span>
                <span class="mx-3"> <img src="../assets/icons/point marron.svg" alt=""></span>
                <span class="align-self-center">+3</span>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'presentCard',
   props: {
     card: Object,
   },
}
</script>

<style>

</style>
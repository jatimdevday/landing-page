<template>
  <div class="container mx-auto flex flex-wrap pt-4 pb-6">
    <div class="w-full">
      <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0" />
    </div>
    <div class="w-full md:w-1/2 p-6 flex flex-col flex-grow flex-shrink">
      <div class="flex-1 overflow-hidden partner">
        <h1 class="italic mb-1 text-center">
          Community Partner
        </h1>
        <div class="flex flex-wrap flex-auto ml-32 mt-8 comm-sec">
          <img src="../assets/images/partner/ngalam.png">
          <img src="../assets/images/partner/pasuruandev.jpg">
          <img src="../assets/images/partner/ixda.png">
          <img src="../assets/images/partner/surabayadev.jpg">
          <img src="../assets/images/partner/surabayapy.jpg">
          <img src="../assets/images/partner/kelas.png">
          <img src="../assets/images/partner/sidoarjodev.jpg">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.partner h1 {
  font-family: "Roboto";
  font-size: 18px;
  font-weight: 500;
  color: #515151;
}

.comm-sec img {
  margin-left: 10px;
  width: 120px;
  height: 100px;
}

.media-sec img {
  margin-left: 40px;
  margin-top: 30px;
  width: 125px;
}
</style>

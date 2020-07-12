<template>
  <div class="row-gap-0 mt-8 mb-4">
    <div class="grid grid-cols-6 gap-4">
      <div class="col-start-1 col-end-4">
        <h1 class="ml-64 italic ">
          Community Partner
        </h1>
        <div class="flex flex-wrap flex-auto ml-24 my-2 comm-sec">
          <img src="../assets/images/partner/ngalam.png">
          <img src="../assets/images/partner/pasuruandev.jpg">
          <img src="../assets/images/partner/ixda.png">
          <img src="../assets/images/partner/surabayadev.jpg">
          <img src="../assets/images/partner/surabayapy.jpg">
          <img src="../assets/images/partner/kelas.png">
          <img src="../assets/images/partner/sidoarjodev.jpg">
          <img src="../assets/images/partner/pasuruandev.jpg">
        </div>
      </div>
      <div class="col-end-7 col-span-2">
        <h1 class="ml-24 italic">
          Media Partner
        </h1>
        <div class="flex flex-wrap flex-auto my-2 media-sec">
          <img
            src="../assets/images/partner/indiekraf.png"
            width="150px"
          >
          <img
            src="../assets/images/partner/riset.png"
            width="120px"
          >
          <img
            src="../assets/images/partner/logodilomalang.png"
            width="120px"
          >
          <img
            src="../assets/images/partner/kawankoding.png"
            width="120px"
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Partner'
}
</script>

<style>
 h1 {
   font-family: 'Roboto';
   font-size: 18px;
   font-weight: 500;
   color: #515151;
 }

 .comm-sec img {
   margin-left: 10px;
   width: 120px;
   height: 100px;
   left: 120px;
   top: 897px;
 }

 .media-sec img {
   margin-left: 20px;
   margin-top: 30px;
   /* width: 140px;
   height: 70px; */
   left: 120px;
   top: 897px;
 }

</style>

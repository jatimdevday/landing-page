<template>
  <div class="container mx-auto flex flex-wrap pt-4 pb-6">
    <div class="w-full">
      <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0" />
    </div>
    <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
      <div class="flex-1 overflow-hidden partner">
        <h1 class="text-center italic mb-1">
          Media Partner
        </h1>
        <div class="flex flex-wrap flex-auto ml-24 mb-20 media-sec">
          <img src="../assets/images/partner/Indiekraf.png">
          <img src="../assets/images/partner/riset.png">
          <img src="../assets/images/partner/logodilomalang.png">
          <img src="../assets/images/partner/kawankoding.png">
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.partner h1 {
  font-family: "Roboto";
  font-size: 18px;
  font-weight: 500;
  color: #515151;
}
.media-sec img {
  margin-left: 50px;
  margin-top: 30px;
  width: 200px;
  object-fit: contain;
}
</style>

<script>
export default {

}
</script>

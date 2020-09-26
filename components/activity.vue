<template>
  <div class="bg-kegiatan">
    <div class="container my-6 mx-auto px-4 md:px-12">
      <div class="text-kg text-center mb-8">
        <br>
        <br>
        <h1 class="text-4xl">
          Kegiatan
        </h1>
      </div>

      <div class="flex flex-wrap -mx-1 lg:-mx-4">
        <div class="my-1 px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3 mb-3">
          <!-- Article -->
          <article class="overflow-hidden rounded-md shadow-md">
            <a href="#">
              <img
                alt="Placeholder"
                class="block "
                src="../assets/images/kegiatan/1.jpeg"
              >
            </a>

            <header class="flex items-center justify-between leading-tight p-2 md:p-4">
              <h1 class="text-lg capitalize font-semibold">
                <a
                  class="no-underline hover:text-gray-800 text-black text-header text-xl"
                  href="#"
                >
                  Webinar JatimDevDay #1
                </a>
              </h1>
            </header>
            <p class="text-detail text-sm mb-5">
              Web Development • June. 26, 2020
            </p>
          </article>
          <!-- END Article -->
        </div>
        <div class="my-1 px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3 mb-3">
          <!-- Article -->
          <article class="overflow-hidden rounded-md shadow-md">
            <a href="#">
              <img
                alt="Placeholder"
                class="block"
                src="../assets/images/kegiatan/2.jpg"
              >
            </a>

            <header class="flex items-center justify-between leading-tight p-2 md:p-4">
              <h1 class="text-lg capitalize font-semibold">
                <a
                  class="no-underline hover:text-gray-800 text-black text-header text-xl"
                  href="#"
                >
                  Webinar JatimDevDay #2
                </a>
              </h1>
            </header>
            <p class="text-detail text-sm mb-5">
              Web Development • June. 26, 2020
            </p>
          </article>
          <!-- END Article -->
        </div>
        <div class="my-1 px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3 mb-3">
          <!-- Article -->
          <article class="overflow-hidden rounded-md shadow-md">
            <a href="#">
              <img
                alt="Placeholder"
                class="block"
                src="../assets/images/kegiatan/3.jpg"
              >
            </a>

            <header class="flex items-center justify-between leading-tight p-2 md:p-4">
              <h1 class="text-lg capitalize font-semibold">
                <a
                  class="no-underline hover:text-gray-800 text-black text-header text-xl"
                  href="#"
                >
                  Webinar JatimDevDay #3
                </a>
              </h1>
            </header>
            <p class="text-detail text-sm mb-5">
              Web Development • June. 26, 2020
            </p>
          </article>
          <!-- END Article -->
        </div>

        <div class="my-1 px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3 mb-3">
          <!-- Article -->
          <article class="overflow-hidden rounded-md shadow-md">
            <a href="#">
              <img
                alt="Placeholder"
                class="block"
                src="../assets/images/kegiatan/4.jpg"
              >
            </a>

            <header class="flex items-center justify-between leading-tight p-2 md:p-4">
              <h1 class="text-lg capitalize font-semibold">
                <a
                  class="no-underline hover:text-gray-800 text-black text-header text-xl"
                  href="#"
                >
                  Webinar JatimDevDay #4
                </a>
              </h1>
            </header>
            <p class="text-detail text-sm mb-5">
              Web Development • June. 26, 2020
            </p>
          </article>
          <!-- END Article -->
        </div>
        <div class="my-1 px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3 mb-3">
          <!-- Article -->
          <article class="overflow-hidden rounded-md shadow-md">
            <a href="#">
              <img
                alt="Placeholder"
                class="block"
                src="../assets/images/kegiatan/5.jpg"
              >
            </a>

            <header class="flex items-center justify-between leading-tight p-2 md:p-4">
              <h1 class="text-lg capitalize font-semibold">
                <a
                  class="no-underline hover:text-gray-800 text-black text-header text-xl"
                  href="#"
                >
                  Webinar JatimDevDay #1
                </a>
              </h1>
            </header>
            <p class="text-detail text-sm mb-5">
              Web Development • June. 26, 2020
            </p>
          </article>
          <!-- END Article -->
        </div>
        <div class="my-1 px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3 mb-3">
          <!-- Article -->
          <article class="overflow-hidden rounded-md shadow-md">
            <a href="#">
              <img
                alt="Placeholder"
                class="block"
                src="../assets/images/kegiatan/6.jpg"
              >
            </a>

            <header class="flex items-center justify-between leading-tight p-2 md:p-4">
              <h1 class="text-lg capitalize font-semibold">
                <a
                  class="no-underline hover:text-gray-800 text-black text-header text-xl"
                  href="#"
                >
                  Webinar JatimDevDay #6
                </a>
              </h1>
            </header>
            <p class="text-detail text-sm mb-5">
              Web Development • June. 26, 2020
            </p>
          </article>
          <!-- END Article -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Activity'
}
</script>

<style>
.bg-kegiatan {
    background: #F6F6F6;
}
.text-kg h1 {
    font-family: Roboto;
    color: #48006C;
}
.text-header {
    margin-left: -10px;
    font-family: Roboto;
    line-height: 23px;
    color: rgba(0, 0, 0, 0.9);
}
.text-detail {
    margin-left: 7px;
    margin-top: -10px;
    font-family: Roboto;
    line-height: 16px;
    color: rgba(0, 0, 0, 0.6);
}
article img {
  width: 380px;
  height: 202px;
}
</style>

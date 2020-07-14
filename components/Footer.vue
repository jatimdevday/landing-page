/* eslint-disable vue/html-indent */
<template>
  <footer class="footer relative py-5 border-b-2 -mt-3">
    <div class="container mx-auto px-6 my-6">
      <div class="sm:flex sm:mt-8">
        <div class="mt-8 sm:mt-0 sm:w-full sm:px-8 flex flex-col md:flex-row justify-between">
          <div class="flex flex-col">
            <span class="font-medium text-black capitalize mb-2 text-top">Jatim Developer Day</span>
            <p class="text-bottom my-2 font-normal">
              Kolaborasi antar komunitas di Jawa Timur yang
              <br>
              berawal dari guyonan di salah satu grup diskusi
              <br>
              komunitas
            </p>
          </div>
          <div class="flex flex-col ">
            <span class="font-medium text-black capitalize mt-4 md:mt-0 mb-2 text-top">Follow Us</span>
            <div class="flex flex-wrap">
              <img src="../assets/images/icons/ig.png">
              <span class="mt-3 mx-3">Jatimdevday</span>
              <img
                src="../assets/images/icons/twitter.jpg"
                class="ml-3"
              >
              <span class="mt-3 ml-3">Jatimdevday</span>
            </div>
          </div>
          <div class="flex flex-col -mr-10">
            <span class="font-medium text-black capitalize mt-4 md:mt-0 mb-2 text-top">Developer Freebies</span>
            <p class="text-bottom my-2 font-normal">
              Download free tools, jQuery and vanilla JavaScript
              <br>
              plugins, and other useful software - developed by
              <br>
              Pixabay.
            </p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
.footer {
    background: #F6F6F6;
}
.text-top {
    font-family: 'Roboto';
    font-size: 24px;
}
.text-bottom {
    font-family: 'Roboto';
    font-size: 16px;
    color: #515151;
}

footer img {
    margin-top: 10px;
    width: 30px;
    height: 30px;
}

.flex .flex-wrap span {
    font-family: Roboto;
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    color: #515151;
}
</style>

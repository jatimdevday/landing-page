<template>
  <footer class="footer relative py-5 border-b-2 -mt-3">
    <div class="container mx-auto px-6 my-6">
      <div class="sm:flex sm:mt-8">
        <div class="mt-8 sm:mt-0 sm:w-full sm:px-8 flex flex-col md:flex-row justify-between">
          <div class="flex flex-col">
            <span class="font-medium text-black capitalize mb-2 text-top text-2xl">Jatim Developer Day</span>
            <p class="text-bottom my-2 font-normal text-base">
              Kolaborasi antar komunitas di Jawa Timur yang
              <br>
              berawal dari guyonan di salah satu grup diskusi
              <br>
              komunitas
            </p>
          </div>
          <div class="flex flex-col ">
            <span class="font-medium text-black capitalize mt-4 md:mt-0 mb-2 text-top text-2xl">Follow Us</span>
            <div class="flex flex-wrap">
              <img src="../assets/images/icons/ig.png">
              <span class="mt-3 mx-3 text-base">Jatimdevday</span>
              <img
                src="../assets/images/icons/twitter.jpg"
                class="ml-3"
              >
              <span class="mt-3 ml-3 text-base">Jatimdevday</span>
            </div>
          </div>
          <div class="flex flex-col -mr-10">
            <span class="font-medium text-black capitalize mt-4 md:mt-0 mb-2 text-top text-2xl">Developer Freebies</span>
            <p class="text-bottom my-2 font-normal text-base">
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
}
.text-bottom {
    font-family: 'Roboto';
    color: #515151;
}

footer img {
    margin-top: 10px;
    width: 30px;
    height: 30px;
}

.flex .flex-wrap span {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 300;
    color: #515151;
}
</style>

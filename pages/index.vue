<template>
  <div>
    <NavBar />
    <!-- tampilan utama -->
    <div class="container-main">
      <!-- judul -->
      <h1 class="title">
        Jatim Developer Day
      </h1>
      <h2 class="subtitle">
        Kolaborasi antar komunitas di Jawa Timur yang berawal dari guyonan <br>
        di salah satu grup diskusi komunitas
      </h2>
      <!-- search bar -->
      <div class="container-searchbar">
        <input
          class="searchbar"
          type="text"
          placeholder="Search community"
        >
        <button>Search</button>
      </div>
    </div>

    <!-- Start Partner Section -->
    <Partner />
    <!-- End Partner Section -->

    <!-- Start Activity Section -->
    <Activity />
    <!-- End Kegiatan Activity -->

    <!-- Start Footer Section -->
    <Footer />
    <!-- End Footer Section -->
  </div>
</template>

<script>
import NavBar from '~/components/navbar.vue'
import Partner from '~/components/partner.vue'
import Activity from '~/components/activity.vue'
import Footer from '~/components/footer.vue'

export default {
  components: {
    NavBar,
    Partner,
    Activity,
    Footer
  }
}
</script>

<style>
/* main */
.container-main {
  background-image: linear-gradient(to bottom right, #50196c, #b61c85);
  @apply h-screen justify-center w-full bg-cover;
}

.title {
  font-family: "Roboto", sans-serif;
  padding-top: 30vh;
  @apply block font-bold text-7xl text-white text-center; /*added font size '7xl' in tailwind.config.js*/
}

.subtitle {
  font-family: "Roboto", sans-serif;
  @apply block font-normal text-xl text-white text-center;
}

/* searchbar */
.container-searchbar {
  @apply pt-10 flex justify-center;
}

.searchbar {
  @apply flex relative border-black rounded-l-lg pl-16 py-4 pr-64;
  @apply inline-block bg-no-repeat;
  background-image: url("../static/search-icon.svg");
  background-position: 5% 50%;
}

.searchbar:focus {
  outline: none;
}

button {
  @apply bg-blue-400 text-white rounded-r-lg p-5;
  background-color: #fa7268;
}

button:focus {
  background-color: rgb(255, 175, 175);
  @apply outline-none;
}
</style>

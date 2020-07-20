// Home Page //
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
import Partner from '~/components/Partner.vue'
import Activity from '~/components/Activity.vue'
import Footer from '~/components/Footer.vue'
import './index.css'

export default {
  components: {
    NavBar,
    Partner,
    Activity,
    Footer
  }
}
</script>

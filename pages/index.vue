// Home Page //
<template>
  <!-- tampilan utama -->
  <div class="container-main">
    <NavBar />
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
</template>

<script>
import NavBar from '~/components/navbar.vue'
import './index.css'

export default {
  components: {
    NavBar
  }
}
</script>

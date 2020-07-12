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
  </div>
</template>

<script>
import NavBar from '~/components/NavBar.vue'
import './index.css'

export default {
  components: {
    NavBar
  }
}
</script>

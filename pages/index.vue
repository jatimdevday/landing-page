<template>
  <div>
    <NavBar />
    <div class="main">
      <h1 class="title">
        Jatim Developer Day
      </h1>
      <h2 class="subtitle">
        Kolaborasi antar komunitas di Jawa Timur yang berawal dari guyonan <br>
        di salah satu grup diskusi komunitas
      </h2>
      <div class="searchbar">
        <input
          class="input"
          type="text"
          placeholder="Search community"
        >
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

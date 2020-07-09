<template>
  <div class="navbar">
    <div class="logo">
      <img
        src="../static/JDD-logo.svg"
        alt="logo JDD"
      >
      <img
        class="textlogo"
        src="../static/JDD-text.svg"
        alt="text logo JDD"
      >
    </div>

    <ul>
      <li>
        <nuxt-link to="/">HOME</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">ABOUT</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
import './NavBar.css'

export default {}
</script>

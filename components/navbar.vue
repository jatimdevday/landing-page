// Navigation Bar Components //
<template>
  <div class="navbar">
    <!-- logo JDD -->
    <div class="logo">
      <a href="/">
        <img
          src="../static/JDD-logo.svg"
          alt="logo JDD"
        >
        <img
          class="textlogo"
          src="../static/JDD-text.svg"
          alt="text logo JDD"
        ></a>
    </div>
    <!-- tombol login dan join -->
    <ul>
      <li class="join">
        <nuxt-link to="/register">
          Join
        </nuxt-link>
      </li>
      <li class="login">
        <nuxt-link to="/login">
          Log In
        </nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
import './navbar.css'

export default {}
</script>

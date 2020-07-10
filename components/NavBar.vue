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
      <li class="join">
        <nuxt-link to="/about">
          Join
        </nuxt-link>
      </li>
      <li class="login">
        <nuxt-link to="/">
          Log In
        </nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
import './NavBar.css'

export default {}
</script>

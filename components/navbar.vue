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

<style>
/* container navbar */
.navbar {
  @apply fixed w-full z-50;
}

/* logo JDD */
.logo img {
  @apply pt-3 pl-24;
  @apply float-left;
}

img.textlogo {
  @apply pt-8 pr-10 pl-4;
}

/* settingan tag 'ul' dan 'li' */
ul {
  @apply pt-3 overflow-hidden list-none;
}

li {
  @apply float-right;
}

li.join {
  background-color: #50196c;
  @apply rounded-full mr-24 text-white text-center;
  @apply block no-underline;
}

li.login {
  @apply mr-8 bg-white text-purple-700;
  @apply block text-center no-underline;
}

li a {
  @apply block text-center text-lg no-underline;
  @apply pt-4 pr-12 pb-4 pl-12;
}

li a:hover:not(.active) {
  background-color: rgb(175, 29, 175);
  @apply rounded-full text-white;
  @apply transition-colors ease-in duration-150;
}

/* nyoba responsive */
@screen sm {
  .navbar {
    @apply bg-white h-16;
  }
}

@screen md {
  .navbar {
    @apply bg-white h-16;
  }
}

@screen lg {
  .navbar {
    @apply bg-white h-20;
  }
}
</style>

<script>
export default {}
</script>

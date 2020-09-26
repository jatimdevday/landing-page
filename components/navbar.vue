<template>
  <div class="fixed w-screen z-50 lg:h-24 bg-white shadow">
    <div class="flex  items-center justify-between flex-wrap h-full mx-0 md:mx-12 lg:mx-24">
      <!-- logo JDD -->
      <a href="/" class="flex">
        <img

          src="../static/JDD-logo.svg"
          alt="logo JDD"
        >
        <img

          src="../static/JDD-text.svg"
          alt="text logo JDD"
        ></a>

      <div class="block lg:hidden">
        <button class="flex items-center bg-white" @click="toggleMenu">
          <!-- <img :src="btnMenu ? '~/assets/images/icons/menu_open-24px.svg':'~/assets/images/icons/menu-24px.svg'"> -->
          <template v-if="btnMenu">
            <img src="~/assets/images/icons/menu_open-24px.svg">
          </template>
          <template v-else>
            <img src="~/assets/images/icons/menu-24px.svg">
          </template>
        </button>
      </div>

      <!-- tombol login dan join -->
      <div class="w-full lg:w-auto " :class="btnMenu ? 'block': 'hidden'">
        <div class="flex flex-col lg:flex-row">
          <nuxt-link to="/register" class="transition duration-300 ease-in-out px-4 py-4 lg:px-12 lg:py-2 lg:mx-2 lg:rounded hover:bg-tombol hover:text-white hover:shadow">
            Join
          </nuxt-link>
          <nuxt-link to="/login" class="transition duration-300 ease-in-out px-4 py-4 lg:px-12 lg:py-2 lg:mx-2 lg:rounded hover:bg-tombol hover:text-white hover:shadow">
            Log In
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      btnMenu: false
    }
  },
  methods: {
    toggleMenu () {
      this.btnMenu = !this.btnMenu
    }
  }
}
</script>

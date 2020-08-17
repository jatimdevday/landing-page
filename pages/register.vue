<template>
  <div class="container-main">
    <NavBar />
    <h1 class="title">
      LOGIN
    </h1>
    <button
      class="bt-google"
      @click="google"
    >
      login with google
    </button>
  </div>
</template>

<script>
import NavBar from '~/components/navbar.vue'
export default {
  components: {
    NavBar
  },
  watch: {
    $route () {
      this.showLoginModal()
    }
  },
  methods: {
    showLoginModal () {
      if (typeof this.$route.query.login !== 'undefined' && this.route.query.login === '1') {
        this.$toast.error('please login', { icon: 'fingerprint' })
        this.$refs.myModalRef.show()
        this.$route.push('/')
      }
    },
    async google () {
      await this.$auth.loginWith('google').catch((e) => {
        this.$toast.show('Error', { icon: 'fingerprint' })
      })
    }
  }
}
</script>

<style>
.container-main {
  background-image: linear-gradient(to bottom right, #50196c, #b61c85);
  @apply h-screen justify-center w-full bg-cover;
}

.title {
  font-family: "Roboto", sans-serif;
  padding-top: 30vh;
  @apply block font-bold text-7xl text-white text-center;
}

.bt-google {
  @apply bg-gray-600 text-white rounded-md mx-64 p-5;
}
</style>

<template>
  <div>
    <div class="columns">
      <div class="column">
        <NavBar />
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <LoginForm/>
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <Footer />
      </div>
    </div>
  </div>
</template>
<script>
import NavBar from '~/components/primary/navbar/index.vue'
import Footer from '~/components/primary/footer/index.vue'
import LoginForm from '~/components/forms/login/index.vue'

export default {
  components: {
    LoginForm,
    NavBar,
    Footer
  }
}
</script>
<style scoped>
</style>

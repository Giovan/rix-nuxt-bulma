<template>
  <div>
    <div class="columns">
      <div class="column">
        <NavBar />
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <SignUpForm />
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
import SignUpForm from '~/components/forms/signup/index.vue'

export default {
  components: {
    NavBar,
    Footer,
    SignUpForm,
  }
}
</script>
<style scoped>
</style>

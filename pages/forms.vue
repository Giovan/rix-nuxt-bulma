<template>
  <div>
    <div class="columns">
      <div class="column">
        <NavBar />
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <div class="left-menu">
          <Menu />
        </div>
      </div>
      <div class="column">
        2
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
import Menu from '~/components/primary/menu/index.vue'
import NavBar from '~/components/primary/navbar/index.vue'
import Footer from '~/components/primary/footer/index.vue'

export default {
  components: {
    Menu,
    NavBar,
    Footer
  }
}
</script>
<style scoped>
</style>

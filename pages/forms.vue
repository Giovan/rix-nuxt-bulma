<template>
  <div>
    <div class="columns">
      <div class="column">
        <NavBar />
      </div>
    </div>
    <div class="columns">
      <div class="column left-menu">
        <Menu />
      </div>
      <div class="column right-column">
        <ContainersForms />
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

import ContainersForms from '~/components/containers/forms/index.vue'

export default {
  components: {
    Menu,
    NavBar,
    Footer,
    ContainersForms
  }
}
</script>
<style scoped>
</style>

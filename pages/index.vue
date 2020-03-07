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
  </div>
</template>
<script>
import Menu from '~/components/primary/menu/index.vue'
import NavBar from '~/components/primary/navbar/index.vue'

export default {
  components: {
    Menu,
    NavBar
  }
}
</script>
<style scoped>
</style>

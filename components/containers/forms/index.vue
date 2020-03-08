<template>
  <div class="columns">
    <div class="column">
      <CreditCard />
      <br/>
      <CreditCard />
    </div>
    <div class="column">
      <CreditCard />
      <br/>
      <CreditCard />
    </div>
  </div>
</template>
<script>
import CreditCard from '~/components/forms/credit-card/index.vue'

export default {
  components: {
    CreditCard,
  }
}
</script>
<style scoped>
</style>

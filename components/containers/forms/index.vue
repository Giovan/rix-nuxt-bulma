<template>
  <div class="columns">
    <div class="column">
      <CreditCard />
      <br/>
      <CreditCard />
    </div>
    <div class="column">
      <Company />
      <br/>
      <CreditCard />
    </div>
  </div>
</template>
<script>
import CreditCard from '~/components/forms/credit-card/index.vue'
import Company from '~/components/forms/company/index.vue'

export default {
  components: {
    CreditCard,
    Company,
  }
}
</script>
<style scoped>
</style>

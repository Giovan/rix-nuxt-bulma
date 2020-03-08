<template>
  <div>
    <div class="columns">
      <div class="column">
        <CreditCard />
      </div>
      <br/>
      <div class="column">
        <Company />
      </div>
    </div>
    <div class="columns">
      <br/>
      <div class="column">
        <BasicForm />
      </div>
      <br/>
      <div class="column">
        <CreditCard />
      </div>
    </div>
  </div>
</template>
<script>
import CreditCard from '~/components/forms/credit-card/index.vue'
import Company from '~/components/forms/company/index.vue'
import BasicForm from '~/components/forms/basic-form/index.vue'

export default {
  components: {
    CreditCard,
    Company,
    BasicForm,
  }
}
</script>
<style scoped>
</style>

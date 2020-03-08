<template>
  <div class="card credit-card credit-card-text margins-card">
    <header class="card-header">
      <p class="card-header-title">
        Company
      </p>
    </header>
    <div class="card-content">
      <div class="field">
        <label class="label">Company</label>
        <div class="control">
          <input class="input" type="text" placeholder="Enter your company name">
        </div>
      </div>

      <div class="field">
        <label class="label">VAT</label>
        <div class="control">
          <input class="input" type="text" placeholder="Please enter your company VAT">
        </div>
      </div>

      <div class="field is-grouped">
        <div class="field padding-right">
          <label class="label">Street</label>
          <div class="control">
            <input class="input" type="text" placeholder="Street name">
          </div>
        </div>

        <div class="field padding-right">
          <label class="label">Postal code</label>
          <div class="control">
            <input class="input" type="text" placeholder="Postal code">
          </div>
        </div>
      </div>

      <div class="field">
        <label class="label">City</label>
        <div class="control">
          <input class="input" type="text" placeholder="City name">
        </div>
      </div>

      <div class="field">
        <label class="label">Country</label>
        <div class="control">
          <input class="input" type="text" placeholder="Country name">
        </div>
      </div>
    </div>
  </div>
</template>
<script>
</script>
<style scoped>
.company-card {
  height: 350px!important;
  text-align: left!important;
}

.margins-card {
  margin-left: -15px;
}

.padding-right {
  padding-right: 25px;
}
</style>

<template>
  <div class="card credit-card credit-card-text margins-card">
    <header class="card-header">
      <p class="card-header-title">
        Credit Card
      </p>
    </header>
    <div class="card-content">
      <div class="field">
        <label class="label">Name</label>
        <div class="control">
          <input class="input" type="text" placeholder="Your name in card">
        </div>
      </div>

      <div class="field">
        <label class="label">Credit Card Number</label>
        <div class="control">
          <input class="input" type="text" placeholder="Credit card number">
        </div>
      </div>

      <div class="field is-grouped">
        <div class="field padding-right">
          <label class="label">Month</label>
          <div class="control">
            <input class="input" type="number" placeholder="1">
          </div>
        </div>

        <div class="field padding-right">
          <label class="label">Year</label>
          <div class="control">
            <input class="input" type="number" placeholder="2021">
          </div>
        </div>

        <div class="field">
          <label class="label">CVV/CVC</label>
          <div class="control">
            <input class="input" type="number" placeholder="123">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
</script>
<style scoped>
.credit-card-text {
  text-align: left!important;
}

.credit-card {
  /* width: 450px!important; */
  height: 350px!important;
}

.margins-card {
  margin-left: -15px;
}

.padding-right {
  padding-right: 25px;
}
</style>

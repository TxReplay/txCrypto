<template>
  <div class="container-fluid">
    <div class="maintable table-responsive">
      <table class="table table-bordered table-hover">
        <thead>
          <tr>
            <th scope="col" colspan="2" rowspan="2"></th>
            <th>Ledger</th>
            <th>Kraken</th>
            <th scope="col" rowspan="2">Add new</th>
          </tr>
          <tr>
            <th>€ Ledger</th>
            <th>€ Kraken</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">BTC</th>
            <td>Total BTC</td>
            <td>Ledger BTC</td>
            <td>Kraken BTC</td>
          </tr>
          <tr>
            <th scope="row">ETH</th>
            <td>Total ETH</td>
            <td>Ledger ETH</td>
            <td>Kraken ETH</td>
          </tr>
          <tr>
            <th scope="row">Add new</th>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainTable',
}
</script>

<style lang="scss" scoped>

</style>

<template> 
  <product-detail :is-edit='true'></product-detail>
</template>
<script>
  import ProductGetDetail from './components/ProductGetDetail'
  export default {
    name: 'getUpdateInfo',
    components: { ProductGetDetail }
  }
</script>
<style>
</style>

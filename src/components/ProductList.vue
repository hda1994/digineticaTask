<template>
  <div class="wrap" >
    <ProductItem v-for="item in items"/>
  </div>
</template>

<script>
import ProductItem from './ProductItem';

export default {
  components: {
    ProductItem
  },
  data() {
    return {
      items: [1, 2, 3,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,11,1]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  display: flex;
  flex-wrap: wrap;
  /*margin: 0 -20px;*/
}
</style>

<template>
  <div class="wrapper">
    <div class="wrap">
      <div class="navbar">
        <CategoryNav/>
        <PriceFilter/>
        <Brands/>
      </div>
      <div class="main">
        <Sort/>
        <TabsFilter/>
        <ProductList/>
        <Pagination/>
      </div>

    </div>
  </div>
</template>

<script>

import ProductList from './ProductList';
import CategoryNav from "./CategoryNav";
import Brands from "./Brands";
import PriceFilter from "./PriceFilter";
import TabsFilter from "./TabsFilter";
import Sort from "./Sort";
import Pagination from "./Pagination";


export default {
  components: {
    Pagination,
    Sort,
    TabsFilter,
    PriceFilter,
    Brands,
    CategoryNav,
    ProductList
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  display: flex;
}

.navbar {
  flex: 0 1 25%;
  padding: 34px 30px 0 0;
}

.main {
  padding: 30px 0 0 0;
  flex: 0 1 75%;
  /*padding: 0 30px;*/
}
</style>

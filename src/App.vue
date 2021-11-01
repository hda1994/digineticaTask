<template>
  <Header/>
  <Search/>
  <Results/>
  <CategoryList/>
  <Content/>
</template>

<script>
import Header from './components/Header';
import Category from './components/CategoryItem';
import CategoryList from './components/CategoryList';
import Search from './components/Search';
import Content from './components/Content';
import Results from './components/Results'

export default {
  components: {
    Header, Category, CategoryList, Search, Content, Results
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, serif;
}

.wrapper {
  width: 100%;
  margin: 0 auto 30px;
  padding: 0 40px;
}


</style>

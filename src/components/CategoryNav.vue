<template>
  <div class="wrap">
    <div class="title">Все категории</div>
    <CategoryNavItem v-for="item in items"/>
    <div class="add_category">Ещё 10 категорий...</div>
  </div>
</template>

<script>
import CategoryNavItem from './CategoryNavItem';

export default {
  components: {
    CategoryNavItem
  },
  data() {
    return {
      items: [1, 2, 3, 4, 5]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  display: flex;
  flex-direction: column;
  margin: -5px 0;
}
.title {
  padding: 5px 0;
}
.add_category {
  padding: 5px 0;
  font-family: Arial,serif;
  font-size: 14px;
  line-height: 16px;
  color: #5375B7;
}
.add_category:hover {
  text-decoration: underline;
  cursor: pointer;
}
</style>

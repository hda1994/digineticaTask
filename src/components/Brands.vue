<template>
  <div class="wrap">
    <div class="title">
      <div class="text">Бренды</div>
      <div class="clear">Очистить</div>
    </div>
    <BrandItem v-for="item in items"/>
  </div>
</template>

<script>
import BrandItem from './BrandItem';

export default {
  components: {
    BrandItem
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
  margin: 22px 0 -5px;
}
.text {
  font-family: Open Sans,serif;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 19px;
}
.clear {
  font-family: Arial,serif;
  font-size: 10px;
  line-height: 11px;
  text-align: right;
  text-decoration-line: underline;
  opacity: 0.5;
}
.clear:hover {
  cursor: pointer;
}

.title {
  padding: 5px 0;
  display: flex;
  justify-content: space-between;
}

.add_category {
  padding: 5px 0;
  font-family: Arial, serif;
  font-size: 14px;
  line-height: 16px;
  color: #5375B7;
}
</style>

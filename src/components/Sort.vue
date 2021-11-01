<template>
  <div class="wrap">
    <div class="tab">Сортировать по: </div>
    <div v-for="item in items" class="tab">
      сортировка
    </div>
    <div class="show">
      <span>показывать по </span>
      <select>
        <option>1</option>
        <option>2</option>
      </select>
    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {
      items: [1, 2, 3]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  margin-bottom: 10px;
  padding-left: 20px;
  display: flex;
  align-items: center;
}
.tab {
  margin-right: 10px;
  /*padding: 7px 15px;*/
}
.show {
  margin-left: auto;
  margin-right: 20px;
  /*padding: 7px 0;*/
}
select {
  padding: 6px 10px;
  border: 1px solid #DEDEDE;
  border-radius: 3px;
  font-family: Open Sans,serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 19px;
  color: #000000;
}
</style>

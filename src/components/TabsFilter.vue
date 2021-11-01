<template>
  <div class="wrap">
    <div v-for="item in items" class="tab">
      Уточнение
    </div>
  </div>
</template>

<script>

export default {
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
  margin-bottom: 5px;
  padding-left: 20px;
  display: flex;
  flex-wrap: wrap;
}
.tab {
  margin-right: 10px;
  padding: 7px 15px;
  background: #FFF3D8;
  font-family: Roboto,serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000000;
  border-radius: 3px;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}
.tab:hover {
  cursor: pointer;
  background: #F1BD45;
}
</style>

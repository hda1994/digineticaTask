<template>
  <div class="item">
    <div class="img"></div>
    <div class="description">
      <div class="name">Название категории</div>
      <div class="count">134 товара</div>
    </div>
  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.img {
  padding: 0 10px;
  height: 60px;
  width: 60px;
  background: #C4C4C4;
  border-radius: 3px;
}
.item {
  padding: 10px;
  flex: 0 1 20%;
  display: flex;
}
.description {
  border-right: 1px solid #B9B9B9;
  padding: 7px 20px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.name {
  font-family: Open Sans,serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 19px;
  color: #333333;
}
.count {
  font-family: Open Sans,serif;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 16px;
  color: #8B8B8B;
}
</style>

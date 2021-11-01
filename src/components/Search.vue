<template>
  <div class="wrapper">
    <form class="wrap">

      <input class="input"/>
      <button class="btn">Найти</button>
      <button class="close">Закрыть</button>
    </form>
  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  display: flex;
}
.input {
  /*width: 78%;*/
  flex: 0 1 78%;
  border: 1px solid #C7C7C7;
  border-radius: 5px 0 0 5px;
  height: 40px;
}

.btn {
  flex: 0 1 12%;
  height: 40px;
  background: #F1BD45;
  border-radius: 0 3px 3px 0;
  border: none;
  font-family: Arial, serif;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000000;
}

.btn:hover {
  cursor: pointer;
}

.close:hover {
  cursor: pointer;
}

.close {
  flex: 0 1 9%;
  /*margin-left: 10px;*/
  margin-left: auto;
  height: 40px;
  border: 1px solid #DEDEDE;
  border-radius: 3px;
  background: #ffffff;
  /*width: 9%;*/
  font-family: Arial, serif;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000000;
}
</style>

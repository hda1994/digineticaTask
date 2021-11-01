<template>
  <div class="wrap">
    <div class="title">Цена, валюта</div>
    <div class="inputs">
      <div>
        <span>от</span>
        <input class="input"/>
      </div>
      <div>
        <span>до</span>
        <input class="input"/>
        <span>р</span>
      </div>
    </div>
    <div class="slider">
    </div>
  </div>
</template>

<script>


export default {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  margin-top: 46px;
  display: flex;
  flex-direction: column;
}

.inputs {
  /*margin: 0 -4.5px;*/
  display: flex;
  flex-wrap: wrap;
}

.inputs span {
  font-family: Arial,serif;
  font-size: 12px;
  line-height: 14px;
  color: #000000;
  opacity: 0.5;
}
.input {
  padding: 12px 13px;
  margin: 10px 5px;
  width: 110px;
  height: 40px;
  border: 1px solid #DEDEDE;
  border-radius: 3px;
  font-family: Arial,serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  color: #000000;
}
.title {
  margin-bottom: 16px;
}

</style>

<template>
  <div class="item">
    <div class="img">
    </div>
    <div class="description">Наименование товара, которое не более 2 строк</div>
    <div class="price">
      <span class="main">
        XX XXX , $
      </span>
      <span class="old">
        XX XXX , $
      </span>
    </div>
    <button class="btn">Кнопка</button>
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
.img {
  height: 260px;
  width: 100%;
  background: #C4C4C4;
  border-radius: 3px;
  margin-bottom: 10px;
}

.item {
  border-radius: 3px;
  padding: 20px;
  flex: 0 1 33.3%;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}
.item:hover {
  box-shadow: 0 0 10px #C4C4C4;
}

.btn {
  border: none;
  background: #F1BD45;
  border-radius: 3px;
  height: 40px;
  width: 100%;
}
.btn:hover {
  cursor: pointer;
}

.description {
  font-family: Arial, serif;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 18px;
  letter-spacing: 0.01em;
}

.price {
  margin-top: 18px;
  margin-bottom: 15px;
}

.main {
  font-family: Open Sans, serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 700;
  line-height: 16px;
  letter-spacing: 0;
  color: #000000;
}

.old {
  font-family: Open Sans, serif;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 16px;
  letter-spacing: 0;
  text-decoration-line: line-through;
  color: #A9A9A9;
}


</style>

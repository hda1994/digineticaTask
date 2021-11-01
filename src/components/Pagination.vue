<template>
  <div class="wrap">
    <div class="prev">2</div>
    <div class="this">3</div>
    <div class="dot">...</div>
    <div class="next">13</div>
    <div class="arrow">></div>
  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap {
  margin-top: 20px;
  display: flex;
  align-items: center;
}
.prev, .this, .next {
  font-family: Arial,serif;
  font-size: 16px;
  line-height: 18px;
  color: #000000;
  opacity: 0.5;
}
.arrow, .dot {
  font-family: Gotham Pro,serif;
  font-size: 18px;
  line-height: 17px;
  color: #000000;
}
.arrow:hover, .dot:hover, .prev:hover, .this:hover, .next:hover {
  cursor: pointer;
  text-decoration: underline;
}
.prev {
  margin-left: 20px;
}
.this {
  opacity: 1;
  margin-left: 30px;
}
.dot {
  margin-left: 10px;
}
.next {
  margin-left: 10px;
}
.arrow {
  margin-left: 17px;
}
</style>

<script setup>
</script>
<template>
  <header>
    <div>
    </div>
  </header>

  <body>
    <div class="docker">
      <div class="docker__item">首页</div>
      <div class="docker__item">订单</div>
      <div class="docker__item">购物车</div>
      <div class="docker__item">我的</div>
    </div>

  </body>
</template>

<style type="scss">
.docker {
  display: flex;
  position: absolute;
  left: 0;
  bottom: 0;
  height: .49rem;
  width: 100%;
  padding: 0 .18rem;
  box-sizing: border-box;
  /*调整计算宽度的模型*/
  background-color: green;
}

.docker__item {
  flex: 1;
  font-size: .12rem;
  text-align: center;
}
</style>

<!---->
<template>
  <div class='tail'>
    <div class="mainbar container">
      <div>
        Created by <span style="color: aqua">XinChen</span>, find me by <a href="https://www.ixinjiu.cn" style="color: cornflowerblue">https://www.ixinjiu.cn</a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Tail',
    data () {
      return {}
    }
  }
</script>
<style scoped>
@import "~assets/css/mediacss.css";

.tail {
  width: 100%;
  min-height: 5em;
  margin-top: 10em;
  background: rgb(39, 39, 39);
  color: rgb(156, 156, 156);
}

.mainbar {
  display: flex;
  justify-content: space-around;
}
</style>

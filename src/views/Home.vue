<template>
  <div class="home">
    <div class="box">
      <span>123</span>
    </div>
    <div class="box2">

    </div>
    <div class="box3">

    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {
  }
}
</script>
<style lang="scss" scoped>
.home {
  .box{
    width: 200px;
    height: 200px;
    background: #42b983;
    font-size: 22px;
  }
  .box2 {
    width: 200px;
    height: 200px;
    margin-left: 200px;
    background: salmon;
  }
  .box3 {
    width: 200px;
    height: 200px;
    margin-left: 400px;
    background: sandybrown;
  }
}
</style>

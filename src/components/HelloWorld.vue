<template>
  <div class="hello">
      <div class="one"></div>
      <div class="two"></div>
      <div class="three"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style lang="less" scoped>
  .hello{
    width: 800px;
    height: 500px;
    border: 1px solid red;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
    div{
      width: 200px;
      height: 200px;
      background: red;
    }
    .one{

    }
  }
</style>

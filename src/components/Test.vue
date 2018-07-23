<template>
    <div class="title">
      <h3>sass test</h3>
      <ul class="content">
        <li>测试1</li>
        <li>测试2</li>
        <li>测试3</li>
      </ul>
    </div>
</template>

<script>
    export default {
      name: "Test"
    }
</script>

<style scoped lang="scss">
  .title{
    color: red;
    .content{
      margin-top: 20px;
      li{
        font-size: 16px;
        color: blue;
      }
    }
  }
</style>

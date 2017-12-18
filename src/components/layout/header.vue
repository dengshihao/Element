<template>
  <div class="header">
    <h2 class="left">element-ui后台管理系统</h2>
    <div class="right">
      <span class="username">someone , welcome to vue </span>
      <el-button type="primary">退出</el-button>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="scss" scoped="">

  .header {
    position: absolute;
    top: 0;
    height: $headerH;
    line-height: $headerH;
    width: 100%;
    background: $mainColor;
    color: white;
    .left {
      float: left;
      font-weight: 100;
      margin-left: 50px;
    }
    .right {
      float: right;
      margin-right: 50px;
      .username {
        margin-right: 30px;
      }
    }
  }
</style>

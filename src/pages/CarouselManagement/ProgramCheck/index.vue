<template>
  <div class="layout">
    <div class="layout-content">
      <div class="layout-router"></div>
    </div>
    <h1>ProgramCheck -- 节目单审核</h1>
  </div>
</template>
<!-- 添加"scoped" 属性限制CSS样式只在当前组件中有效 -->
<style scoped>
  .layout{
    padding-left: 30%;
    padding-right: 30%;
    background-color: orange;
  }
</style>
<!-- 添加type="es6" 属性使其支持ES6语法 -->
<script type="es6">
  export default {
    name: 'ProgramCheck'
  }
</script>

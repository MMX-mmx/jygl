<template>
  <el-breadcrumb separator-class="el-icon-arrow-right">
    <el-breadcrumb separator="/">
      <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">{{$route.meta.title}}</a>
      </el-breadcrumb-item>
    </el-breadcrumb>
  </el-breadcrumb>
</template>

<script>
export default {
  name: "",
  data() {
    return {};
  },
  components: {}
};
</script>


<style scoped>
.el-breadcrumb {
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 12px 0 rgba(0, 0, 0, 0.1);
}
.main .line {
  border-left: 3px solid red;
  padding-left: 10px;
}
</style> 
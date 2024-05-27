<template>
  <div>
    <el-container>
      <el-header style="height: 148px; padding: 0"><Header></Header></el-header>
      <el-main>Main</el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>

<script>
import Header from "../components/Header.vue";
export default {
  name: "MyMain",
  components: {
    Header,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
a {
  text-decoration: none;
  color: #fff;
}
li {
  list-style: none;
}
.clearfix:after {
  content: "";
  display: table;
}

.clearfix:after {
  clear: both;
}
.w {
  width: 1200px;
}
</style>
<template>
  <div class="common-layout">
    <el-container class="Container">
      <el-header class="Header">Header</el-header>
      <el-main class="Main">Main</el-main>
      <el-footer class="Footer">Footer</el-footer>
    </el-container>
  </div>
</template>
<style scoped>
.common-layout{
  height: 100%;
}
.Container{
  height: 100%;
}
.Header{
  background-color: rgb(189, 189, 236);
  height: 25%;
 border-radius: 20px;
}
.Main{
  width: 100%;
  background-color: turquoise;
  height: 50%;
  background-image: url('./monitor-2.svg');
  background-position: 50% 47%;
  background-repeat: no-repeat;
  background-size: cover;
 
}
.Footer{
  background-color:rgb(189, 189, 236);
  height: 25%;
}
</style>
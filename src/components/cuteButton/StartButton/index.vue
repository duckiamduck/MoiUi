<template>
  <div > 
      <el-button class="MoiButton"></el-button>
  </div>
</template>
<script setup lang="ts">


</script>
<style scoped>
.MoiButton{
  width: 50px;
  height: 50px;
  color: white;
  border: none;
  background-color: pink;
  border-radius: 15px; 
  background-image: url('./sad.svg');
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
}
.MoiButton:active{
  box-shadow: 0 0 5px 5px rgba(223, 131, 174, 0.5);
  width: 100px;
  background-image: url('./happy.svg');
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
}
</style>
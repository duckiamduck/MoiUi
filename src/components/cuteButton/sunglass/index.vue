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
  background-color: pink;
  border: none;
  border-radius: 15px;
background-image: url('./take.svg');
background-size: contain;
background-position: center;
background-repeat: no-repeat;
}
.MoiButton:hover{
width: 100px;

background-size: 30%;
background-position: 45% 50%;
background-repeat: no-repeat;
background-image:url('./sunglass.svg');
background-size: 50%;
}
.MoiButton:active{
box-shadow: 0 0 5px 5px rgba(223, 131, 174, 0.5);
background-image: url('./cry.svg');
background-size: contain;
background-position: center;
background-repeat: no-repeat;
}
</style>
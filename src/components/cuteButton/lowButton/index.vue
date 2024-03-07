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
  border-radius: 50px;
background-image: url('./low.svg');
background-size: 70%;
background-position: center;
background-repeat: no-repeat;
}

.MoiButton:active{
box-shadow: 0 0 5px 5px rgba(223, 131, 174, 0.5);
color: red;
background-size: contain;
background-position: center;
background-repeat: no-repeat;
transform: rotate(0.5turn) ;
transition-timing-function: 5s;
}
</style>
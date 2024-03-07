<template>
  <div > 
      <el-button class="MoiButton" @click="Caution()"></el-button>

  </div>
</template>
<script setup lang="ts">
import { ElMessageBox } from 'element-plus';


const Caution = ()=>{
  ElMessageBox.alert('Caution', 'Carefully', {
    // if you want to disable its autofocus
    autofocus: false,
    confirmButtonText: 'OK',
  })
}
</script>
<style scoped>
.MoiButton{
  width: 50px;
  height: 50px;
  color: white;
  background-color: pink;
  border: none;
  border-radius: 15px;
background-image: url('./caution.svg');
background-size: contain;
background-position: center;
background-repeat: no-repeat;
}
</style>
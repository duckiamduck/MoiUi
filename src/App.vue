<template>
  <div class="main">
<ButtonBlock></ButtonBlock>

<div class="ContainerBlock">
<Container></Container>
</div >

  <div class="PasteBlock">
    <panda></panda>
  </div>

  <div class="MenuBlock">
<moiMenu></moiMenu>
  </div>
  
  <div class="CuteButtonBlock">

<Star></Star>
<Joker></Joker>
<Toolow></Toolow>
  </div>
  </div>


</template>

<script lang="ts" setup>
import ButtonBlock from '@/view/normalButton/index.vue'
//

import Container from './components/Container/P3r/index.vue'

//past
import panda from './components/PastePaper/Panda/index.vue'

//menu
import moiMenu from './components/menu/index.vue'


//cutebutton
import Star from './components/cuteButton/StartButton/index.vue'
import Joker from '@/components/cuteButton/sunglass/index.vue'
import Toolow from '@/components/cuteButton/lowButton/index.vue'
</script>


<style scoped >
 .main{
  display: flex;
  flex-direction: row;
  flex-wrap:wrap;
  width: 100%;
  height: 100%;
  background-color: rgb(221, 144, 144);
  border-radius: 15px;
 }


 .ContainerBlock{
  width: 50%;
  height: 500px;
  border-radius: 15px;
  background-color: rosybrown;
  margin:0 15px 0 20px;
 }
 .PasteBlock{
  width: 24%;
  height: 500px;
  display: flex;
  border-radius: 15px;
  flex-direction: row;
  flex-wrap:wrap;
  justify-content:center;
  background-color: rosybrown;
 }
 .MenuBlock{
  width:24%;
  height:500px;
  margin: 10px;
 }
 .CuteButtonBlock{
  width: 25%;
  height: 500px;
  background-color: rosybrown;
  border-radius: 15px;
  box-sizing: border-box;
  background-image: v-text="sb";
  padding: 5px;
  margin: 10px;
  display: flex;
  flex-direction: row;
 }
</style>
<template>
  <div class="main">
    <div class="ButtonBlock">
      <Button></Button>
      <CautionButton></CautionButton>
      <LocationButton></LocationButton>
      <HomeButton></HomeButton>

      <SettingButton></SettingButton>
      <RefreshButton></RefreshButton>
      <DownUpButton></DownUpButton>
      <clButton></clButton>
      <AddButton></AddButton>
    </div>

<div class="ContainerBlock">
<Container></Container>
</div >

  <div class="PasteBlock">
    <panda></panda>
  </div>

  <div class="MenuBlock">
<moiMenu></moiMenu>
  </div>
  
  </div>

</template>

<script lang="ts" setup>
//button
import Button from './components/Button/dangerbutton/index.vue'
import CautionButton from './components/Button/cuationbutton/index.vue'
import LocationButton from './components/Button/locationbutton/index.vue'
import HomeButton from './components/Button/homebutton/index.vue'
import SettingButton from './components/Button/settingbutton/index.vue'
import RefreshButton from './components/Button/refreshbutton/index.vue'
import DownUpButton from './components/Button/downupbuttoin/index.vue'
import clButton from './components/Button/colectionbutton//index.vue'
import AddButton from './components/Button/addbutton/index.vue'

//

import Container from './components/Container/P3r/index.vue'

//past
import panda from './components/PastePaper/Panda/index.vue'

//menu
import moiMenu from './components/menu/index.vue'

</script>


<style scoped>
 .main{
  display: flex;
  flex-direction: row;
  flex-wrap:wrap;
  width: 100%;
  height: 100%;
  background-color: rgb(221, 144, 144);
  border-radius: 15px;
 }
 .ButtonBlock{
  width: 24%;
  height: 500px;
  display: flex;
  border-radius: 15px;
  flex-direction: row;
  flex-wrap:wrap;
  justify-content:center;
  background-color: rosybrown;
 }
 .ContainerBlock{
  width: 50%;
  height: 500px;
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
  width:30%;
  height:500px;

 }
</style>
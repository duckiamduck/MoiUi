<template>
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

</template>

<script lang="ts" setup>
//button
import Button from '@/components/Button/dangerbutton/index.vue'
import CautionButton from '@/components/Button/cuationbutton/index.vue'
import LocationButton from '@/components/Button/locationbutton/index.vue'
import HomeButton from '@/components/Button/homebutton/index.vue'
import SettingButton from '@/components/Button/settingbutton/index.vue'
import RefreshButton from '@/components/Button/refreshbutton/index.vue'
import DownUpButton from '@/components/Button/downupbuttoin/index.vue'
import clButton from '@/components/Button/colectionbutton//index.vue'
import AddButton from '@/components/Button/addbutton/index.vue'

</script>

<style scoped>
.ButtonBlock
{
 width: 24%;
 height: 500px;
 display: flex;
 border-radius: 15px;
 flex-direction: row;
 flex-wrap:wrap;
 justify-content:center;
 background-color: rosybrown;
 box-sizing: border-box;
 padding: 5px;
}

</style>
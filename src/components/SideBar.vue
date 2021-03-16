<template>
  <div class="container mx-auto">
    <div class="flex items-start pt-4">
      <!-- LeftSideBar -->
      <LeftSideBar></LeftSideBar>
      <!-- LeftSideBar -->

      <!-- Center -->
      <CenterBar></CenterBar>
      <!-- Center -->

      <!-- RightSideBar -->
      <RightSideBar></RightSideBar>
      <!-- RightSideBar -->
    </div>
  </div>
</template>

<script>
import LeftSideBar from './LeftSideBar'
import CenterBar from './CenterBar'
import RightSideBar from './RightSideBar'

export default {
  components: {
    LeftSideBar,
    CenterBar,
    RightSideBar
  }
}
</script>

<style>
.container {
  max-width: 970px;
}
</style>
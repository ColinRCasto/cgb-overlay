<template lang="pug">
  #app
    #right-container
      camera-view
      name-view
      timer-view
    hd-view
</template>

<script>
import HdView from '@/components/HdView'
import TimerView from '@/components/TimerView'
import StdView from '@/components/StdView'
import CameraView from '@/components/CameraView'
import NameView from '@/components/NameView'
export default {
  name: 'app',
  components: {
    HdView,
    StdView,
    TimerView,
    CameraView,
    NameView
  }
}
</script>

<style lang="scss">
  @import '@/scss/base.scss';

  #app {
    width: 1600px;
    height: 840px;
    //background: linear-gradient(45deg, $void, $jewel);
    display: flex;
    flex-flow: row nowrap;
    justify-content: space-around;
  }

  #right-container{
    flex-grow: 1;
    display: flex;
    flex-flow: column nowrap;
    justify-content: flex-start;
    align-items: center;
  }
</style>

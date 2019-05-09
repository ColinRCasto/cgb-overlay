<template lang="pug">
  .timer
</template>

<script>
export default {
  name: 'TimerView'
}
</script>

<style lang="scss" scoped>
  .timer{
    width: 350px;
    height: 262px;
    border: 5px solid $stark;
    border-radius: 4px;
    box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    opacity: 1;
    margin-top: 25vh;

    &:after{
      box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    }
  }
</style>

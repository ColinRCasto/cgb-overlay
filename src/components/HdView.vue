<template lang="pug">
  .game-hd
</template>

<script>
export default {
  name: 'HdView'
}
</script>

<style lang="scss" scoped>
  .game-hd{
    width: 1280px;
    height: 720px;
    border: 5px solid $stark;
    border-radius: 4px;
    box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    margin: auto;
    opacity: 1;

    &:after{
      box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    }
  }
</style>

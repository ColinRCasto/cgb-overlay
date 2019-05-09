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
    width: 768px;
    height: 728px;
    border: 5px solid $stark;
    border-radius: 4px;
    box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    margin: auto;
    opacity: 1;
    margin-right: 10rem;

    &:after{
      box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    }
  }
</style>

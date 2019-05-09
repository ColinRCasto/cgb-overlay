<template lang="pug">
  .name
</template>

<script>
export default {
  name: 'NameView'
}
</script>

<style lang="scss" scoped>
  .name{
    width: 325px;
    height: 75px;
    border: 5px solid $stark;
    border-radius: 4px;
    box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    opacity: 1;
    margin-top: 5vh;
    background:linear-gradient(90deg,$jewel,$fuschia);

    &:after{
      box-shadow: 0 0 20px $stark, 0 0 40px $fuschia, 0 0 60px $jewel;
    }
  }
</style>

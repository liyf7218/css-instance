<template lang="html">
  <div class="flex">
    <div class="basic-flex">
      <div class="item">1</div>
      <div class="item">2</div>
      <div class="item">3</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BasicFlex',
  data(){
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
.basic-flex {
  width: 100%;
  height: 500px;
  display: flex;

  .item {

  }
}
</style>

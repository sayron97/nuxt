<template>
  <div class="row">
    <div class="col">
      <div class="row information-row">
        <b-img src="/Group_1086.svg" class="information-icon"></b-img>
        <div class="information-text">{{name}}</div>
      </div>
    </div>
    <div class="col">
      <div class="row information-row">
        <div class="information-text-value">{{fieldValue}}</div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
      name: "InformationRow",

      props: {
        name: String,
        fieldValue: String,
      }
    }
</script>

<style lang="scss" scoped>
  @import '~assets/scss/components/information.scss';
</style>

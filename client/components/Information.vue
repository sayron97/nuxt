<template>
  <div class="main">
    <div class="link-form">
       <a class="link" href="#">Информация</a>
    </div>
    <hr>
    <information-row name="Образование" fieldValue="бакалавр"></information-row>
    <information-row name="Локация" fieldValue="Львов, Украина"></information-row>
    <information-row name="Дата рождения" fieldValue="25.12.1997"></information-row>
    <information-row name="Хобби" fieldValue="Певас"></information-row>
    <information-row name="Про себя" fieldValue="Пью певас"></information-row>
    <div id="demo" class="collapse">
      <information-row name="Образование" fieldValue="бакалавр"></information-row>
      <information-row name="Образование" fieldValue="бакалавр"></information-row>
    </div>
    <hr class="down">
    <button class="show-more" data-toggle="collapse" data-target="#demo">Показать больше</button>
  </div>
</template>

<script>
  import InformationRow from '~/components/InformationRow.vue'

    export default {
        name: "Information",
        components: {
        InformationRow
      }
    }
</script>

<style lang="scss" scoped>
  @import '~assets/scss/components/information.scss';
</style>

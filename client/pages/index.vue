<template>
  <section class="container">
    <user-header></user-header>
      <div class="row main-body">
        <div class="col-sm">
          <information></information>
          <album element="фото" albumType="Фотоальбомы" img1="wow1.jpg" img2="wow2.jpg" img3="wow4.jpeg" img4="wow4.jpeg" countElement="88"></album>
          <album element="видео" albumType="Видеоальбомы" img1="wow4.jpeg" img2="wow1.jpg" img3="wow2.jpg" img4="wow2.jpg" countElement="254"></album>
          <friends></friends>
        </div>
        <div class="col-sm">
          Одна из трёх колонок
        </div>
        <div class="col-sm">
          Одна из трёх колонок
        </div>
      </div>
  </section>
</template>

<script>
import UserHeader from '~/components/UserHeader.vue'
import Information from '~/components/Information.vue'
import Album from '~/components/Album.vue'
import Friends from '~/components/Friends.vue'

export default {
  components: {
      UserHeader,
      Information,
      Album,
      Friends
  }
}
</script>

<style lang="scss" scoped>
  @import '~assets/scss/elements/page.scss';
</style>


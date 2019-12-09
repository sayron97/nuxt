<template>
  <div class="main">
    <div class="link-form">
      <a class="link" href="#">{{ albumType }} ({{ countElement }})</a>
    </div>
    <hr>

    <div class="row">
      <div class="col-sm first">
        <div class="img-block" v-bind:style='{ background: "url(_nuxt/static/" + img1 + ")",
         backgroundSize: "cover",backgroundPosition: "center"}'></div>
      </div>
      <div class="col-sm">
        <div class="img-block" v-bind:style='{ background: "url(_nuxt/static/" + img2 + ")",
         backgroundSize: "cover",backgroundPosition: "center"}'></div>
      </div>
      <div class="col-sm last">
        <div class="img-block" v-bind:style='{ background: "url(_nuxt/static/" + img3 + ")",
         backgroundSize: "cover",backgroundPosition: "center"}'></div>
      </div>
    </div>

    <div class="col">
      <div class="black-background" @mouseover="mouseOver" @mouseleave="mouseOver">
         <div class="img-block-bottom" v-bind:style='{ background: "url(_nuxt/static/" + img4 + ")",
         backgroundSize: "cover",backgroundPosition: "center"}'></div>
         <div v-if="active" class="more-photo">
            {{ countElement }} {{ element}}
         </div>
      </div>
    </div>

  </div>
</template>

<script>
    export default {
      name: "Album",
      props: {
        albumType: String,
        active: false,
        img1: String,
        img2: String,
        img3: String,
        img4: String,
        element: String,
        countElement: Number
      },
      methods: {
        mouseOver: function () {
          this.active = !this.active;
        }
      },
    }
</script>

<style lang="scss" scoped>
  @import '~assets/scss/components/album.scss';
</style>


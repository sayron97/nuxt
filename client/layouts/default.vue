<template>
  <div class="main">
    <top-header/>
    <main id="main" role="main">
      <nuxt></nuxt>
    </main>
  </div>
</template>

<script>
    import Vue from 'vue'
    import BootstrapVue from 'bootstrap-vue'

    Vue.use(BootstrapVue)

    import TopHeader from '~/components/TopHeader.vue'

    export default {
        components: {
            TopHeader
        },
        head: {
            script: [
                { src: 'https://code.jquery.com/jquery-3.3.1.slim.min.js' },
                { src: 'https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js' },
                { src: 'https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js' },
            ],
            link: [
                { rel: 'stylesheet', href: 'https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css',
                    integrity: 'sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T',
                    crossorigin: 'anonymous'}
            ]
        }
    }
</script>

<style lang="scss">
  @import '~assets/scss/styles.scss';
</style>

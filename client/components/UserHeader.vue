<template>
    <div class="bg-wrapper">
      <img src="/user_header_back.png" class="user-header-back" alt="" />
      <b-container class="bv-example-row">
        <b-row>
          <b-col cols="3">
            <b-img src="/main_pic.png" class="main_user_image" rounded="circle" alt="Circle image"></b-img>
          </b-col>
          <b-col cols="9">

            <a href="http://example.com" class="download">Змiнити головне фото</a>

            <div class="name-block">
               <div class="name">Maxim Babichev</div>
               <div class="status">Я сегодня в чудесном настроении!</div>
            </div>

            <ul class="nav">
              <li class="nav-item">
                <b-img src="/house.png" class="main-navbar-image"></b-img>
                <a class="nav-link" href="#">Главная</a>
              </li>
              <li class="nav-item">
                <b-img src="/i.png" class="main-navbar-image"></b-img>
                <a class="nav-link" href="#">Информация</a>
              </li>
              <li class="nav-item">
                <div class="main-navbar-number">20</div>
                <a class="nav-link" href="#">Друзья</a>
              </li>
              <li class="nav-item">
                <div class="main-navbar-number">45</div>
                <a class="nav-link" href="#">Фото</a>
              </li>
              <li class="nav-item">
                <div class="main-navbar-number">7</div>
                <a class="nav-link" href="#">Видео</a>
              </li>
              <li class="nav-item">
                <b-img src="/dots.png" class="dots"></b-img>
                <a class="nav-link" href="#">Еще</a>
              </li>
            </ul>

          </b-col>
        </b-row>
      </b-container>
    </div>
</template>

<script>
    export default {
        name: "UserHeader"
    }
</script>

<style lang="scss">
  @import '~assets/scss/components/user_header.scss';
</style>

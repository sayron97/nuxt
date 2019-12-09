<template>
    <nav class="navbar navbar-expand-lg">
      <div class="container">
      <a class="navbar-brand" href="#">
        <b-img src="/esvoe.png" class="esvoe-img" alt="Icon"></b-img>
        <b-img src="/svoe.png" class="svoe-img" alt="Icon"></b-img>
      </a>
      <a class="navbar-brand" href="#">
        <b-img src="/white_circle.png" class="white-cirle" alt="Icon"></b-img>
      </a>

      <div class="input-group">
        <input type="text" placeholder="Поиск.." class="search-input">
        <div class="input-group-append">
          <span class="input-group-text">
            <b-img src="/PIKTOGRAM-61.svg" class="lupa" alt="Icon"></b-img>
          </span>
        </div>
      </div>


      <a class="navbar-brand" href="#">
      <b-img src="/main_pic.png" rounded="circle" class="small-user-img" alt="Circle image"></b-img>
      </a>

      <div class="dropdown">
        <button class="btn dropdown-toggle header-dropdown" type="button" data-toggle="dropdown">
        </button>
        <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
        </div>
      </div>

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <a class="navbar-brand" href="#">
        <b-img src="/PIKTOGRAM-63.svg" class="sidebar-icon" alt="Icon"></b-img>
      </a>

      <a class="navbar-brand" href="#">
        <b-img src="/PIKTOGRAM-62.svg" class="sidebar-icon" alt="Icon"></b-img>
      </a>

      <a class="navbar-brand" href="#">
        <b-img src="/PIKTOGRAM-64.svg" class="sidebar-icon" alt="Icon"></b-img>
      </a>

      <a class="navbar-brand" href="#">
        <b-img src="/PIKTOGRAM-66.svg" class="sidebar-icon" alt="Icon"></b-img>
      </a>

      </div>
    </nav>
</template>

<style lang="scss">
  @import '~assets/scss/components/header.scss';
</style>

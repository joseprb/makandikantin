<template>
<nav class="navbar navbar-expand-lg navbar-light bg-white h-25 nav-o font-of fontc-o">
  <router-link to="/Home" class="navbar-brand"><img src="../assets/img/logo-ofood.png" class="logo-o"></router-link>
  <button class="navbar-toggler pt-3 pb-3 border-white" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse pt-3" id="navbarNavAltMarkup">
    <ul class="navbar-nav ml-auto">
      <form class="form-inline pb-2">
        <div class="shadow-sm bg-white rounded">
          <input class="form-control border-0 font14-of" type="search" placeholder="Cari..." aria-label="Search">
          <button class="btn btn-light bg-white border-0 fontc-5-of" type="submit"><img src="../assets/img/i-search.svg"></button>
        </div>
      </form>
      <li  class="nav-item">
        <a class="nav-link" href="#"><img src="../assets/img/i-notification.svg"></a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle font-weight-bold fontc-5-of" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          <img class="userimg-of pr-1" src="../assets/img/kucing.jpg">Admin
        </a>
        <div class="dropdown-menu fontc-1-of" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Profil</a>
          <a class="dropdown-item" href="#">...</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Keluar</a>
        </div>
      </li>
    </ul>
  </div>
</nav>
</template>

<script>

</script>

<style scoped>

</style>

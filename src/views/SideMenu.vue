<template>
    <!-- uma barra de navegação com o nome e o símbolo da Spotify -->

<nav class=" navbar fixed-top navbar-expand-lg  navbar-dark " style="background-color: rgb(0, 0, 0);">
    <!-- img + LINK -->
  <div class="container-fluid">
      <a class="navbar-brand" href="#">
          <img src="../../assets/spotifyGreen.svg" width="50" height="60" class="d-inline-block align-center" alt="navBar"> Spotify
      </a>

      <!-- button para responsivo navBar -->
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navBarSide"><span class="navbar-toggler-icon"></span> </button>

      <div class="collapse navbar-collapse" id="navBarSide">
          <!-- lista de itens de menu  -->
          <ul class="navbar-nav ml-auto">
              <li class="nav-item">
                  <a class="nav-link " routerLink="/home"> Home </a>
              </li>
              <li class="nav-item">
                  <a class="nav-link " routerLink="/help"> Ajuda </a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#"> Baixar </a>
              </li>
          </ul>
      </div>
  </div>
</nav>
</template>

<style scoped>

nav img.spotify {
    margin-right: 1.5rem;
    margin-left: 0.5rem;
}

* a:hover {
    color: rgb(67, 223, 19);
}

* li>a:hover {
    color: rgb(67, 223, 19);
}


</style>
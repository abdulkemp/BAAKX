<template>
    <div>
        <div class="collapse" id="navbarToggleExternalContent">
  <div class="bg-dark p-4">
    <h5 class="text-white h4">Collapsed content</h5>
    <span class="text-muted">Toggleable via the navbar brand.</span>
  </div>
</div>

<nav class="navbar navbar-dark bg-dark fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"> <i class="fa-solid fa-brands fa-bitcoin fa-flip"></i> BAAAKX</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="offcanvas bg-dark offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasNavbarLabel" style="color:white;">BAAAKX</h5>
        <button type="button" class="btn-close btn-close-white text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
          <li class="nav-item">
            <a class="nav-link" href="#"><router-link to="/"></router-link>Home<i class="fa fa-home" aria-hidden="true"></i></a>
            <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
          </li>
<li class="nav-item">
            <a class="nav-link" href="#">Profile <i class="fa fa-user" aria-hidden="true"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Edit <i class="fa fa-pencil-square" aria-hidden="true"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Add Account <i class="fa fa-plus-square" aria-hidden="true"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">History <i class="fa fa-history" aria-hidden="true"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Buy <i class="fa fa-pencil-square" aria-hidden="true"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Credit <i class="fa fa-credit-card" aria-hidden="true"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact <i class="fa fa-compress" aria-hidden="true"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Help <i class="fa fa-info-circle" aria-hidden="true"></i></a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </div>
</nav>
</div>
        <!-- <nav>
            <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
        </nav> -->
</template>

<script>
    export default {
        name : "Navbar"
    }
</script>

<style scoped>
i{
    color: gold;
}
/* .btn-close{
    background-color: white !important;
} */
</style>
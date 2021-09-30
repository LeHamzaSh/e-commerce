<template>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Navbar Contents -->
      <div class="collapse navbar-collapse show" id="navbarTogglerDemo01">
        <a class="navbar-brand justify-content-left" href="#">Hamza's Website</a>
        <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
          <li class="active nav-item"><router-link to="/"><button class="btn btn-danger">All Items</button></router-link></li>
          <li class="nav-item"><router-link to="/about"><button class="btn btn-danger">Add Items</button></router-link></li>
          <li class="nav-item"><button class="btn btn-danger disabled">Categories</button></li>
        </ul>
      </div>

  </nav>

  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*background-image: url("./assets/bg.jpg");*/
}

.navbar-collapse{
  justify-content: center;
  padding-left: 15px;
  padding-right: 15px;
}

.nav-item, .nav-item :active{
  justify-content: center;
  padding-left: 20px;
  padding-right: 20px;
}

</style>

<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">32-Bits</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
             <router-link class="nav-link" to="/">Inicio</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/search">Busqueda</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/sealing" class="nav-link">Ventas</router-link>
            </li>
            <li class="nav-item">
             <router-link to="/total" class="nav-link">Total</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style>
</style>
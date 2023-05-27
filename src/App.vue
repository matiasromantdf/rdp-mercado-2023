<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div class="container">
    <div class="">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-md">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Features</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Pricing</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>

    <RouterView />
  </div>
</template>

<style>
.material-symbols-outlined {
  font-size: 40px;
  font-weight: 10;
  border: 1px solid black;
  border-radius: 5px;
  background-color: #c3d9f7;

}



/* que el navbar despliegue lento */
.navbar-collapse {
  transition: height 0.7s ease-in-out;
}

/* que el navbar se superponga  */
.navbar {
  position: fixed;
  z-index: 1;
}
</style>

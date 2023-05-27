<template>
  <div class="container">
    <input type="text" id="txtBusqueda" placeholder="estoy buscando...">
    <button class="boton-buscar">Buscar</button>
  </div>
</template>

<script>
export default {
  setup() {


    return {}
  }
}
</script>

<style scoped>
#txtBusqueda {
  width: 100%;
  height: 60px;
  border: 1px solid rgb(168, 164, 164);
  border-radius: 5px;
  padding: 5px;
  font-size: 20px;
  max-width: 500px;
  opacity: 0.5;
  color: rgb(11, 5, 92);
  box-shadow: 0px 0px 10px 0px rgb(0 0 0 / 50%);
}

.container {
  background-image: linear-gradient(to right, #312858 0%, #a6c1ee 51%, #508fee 100%);
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.boton-buscar {
  width: 100px;
  height: 60px;
  border: 1px solid rgb(168, 164, 164);
  border-radius: 5px;
  padding: 5px;
  font-size: 20px;
  max-width: 500px;
  opacity: 0.5;
  color: rgb(11, 5, 92);
  box-shadow: 0px 0px 10px 0px rgb(0 0 0 / 50%);
  background-color: #c3d9f7;
  margin-left: 2px;
}
</style>
<template>
  <div class="contenedor">
    <input type="text" name="" id="" v-model="this.valor" />
    <i class="bi bi-search lupa"></i>
  </div>
</template>
<script>
export default {
  name: "BuscadorComponent",
  data() {
    return {
      valor: "",
    };
  },
};
</script>
<style scoped>
.contenedor {
  position: relative;
  width: 26vw;
  height: 7vh;
}
input {
  width: 100%;
  height: 100%;
  border-radius: 20px;
  border: none;
  background: #f5f5f5;
}
.lupa {
  color: #e07024;
  font-size: 27px;
  position: absolute;
  right: 1.5rem;
  margin-top: 1%;
}
@media (max-width: 800px) {
  .contenedor {
    width: 40vw;
  }
}
@media (max-width: 1200px) {
  .contenedor {
    width: 50vw;
  }
}
</style>

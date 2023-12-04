<template>
  <div class="contenedor">
    <img src="@/assets/images/LogoSacantaBlanco.svg" alt="" />
    <h5 class="direccion">
      <strong class="strong">Municipalida de Sacanta | </strong>
      25 de Mayo 292, Sacanta, Cordoba | CP X5945 | TEL.: 03533 15 417923
    </h5>
  </div>
</template>
<script>
export default {
  name: "FooterComponent",
};
</script>
<style scoped>
.contenedor {
  width: 100%;
  height: 38vh;
  background: linear-gradient(90deg, #e52320 0.07%, #ffcc03 106.28%);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
img {
  width: 21%;
}
.direccion {
  color: white;
  font-weight: 300;
  line-height: normal;
  letter-spacing: 1px;
  margin-top: 3rem;
}
.strong {
  font-weight: 600;
}
@media (max-width: 800px) {
  .contenedor {
    text-align: center;
  }
  .direccion {
    font-weight: 200;
  }
}
</style>

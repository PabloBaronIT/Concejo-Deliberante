<template>
  <div class="contenedor">
    <img src="@/assets/images/LogoSacantaBlanco.svg" alt="" />
  </div>
</template>
<script>
export default {
  name: "FooterComponent",
};
</script>
<style scoped>
.contenedor {
  width: 100vw;
  height: 30vh;
  background: linear-gradient(90deg, #e52320 0.07%, #ffcc03 106.28%);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
img {
  width: 20vw;
}
</style>

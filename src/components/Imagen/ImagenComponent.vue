<template>
  <div class="contenedor"></div>
  <!-- <div class="capa"></div> -->
</template>

<style scoped>
.contenedor {
  position: relative;
  width: 100%;
  height: 65vh;
  background: linear-gradient(356deg, #000 0.95%, rgba(0, 0, 0, 0) 45.9%);

  background-image: url("@/../public/images/foto.png");
  background-size: contain;
  background-repeat: no-repeat;
  z-index: 1;
  overflow: hidden;
}
.capa {
  position: absolute;
  background-size: contain;

  width: 100%;

  height: 86vh;
  background: linear-gradient(
    272deg,
    #000 -23.75%,
    rgba(0, 0, 0, 0) 55.14%,
    #000 114.38%
  );
}
@media (max-width: 600px) {
  .contenedor {
    height: 55vh;
    background-size: contain;
  }
}
@media (max-width: 800px) {
}
@media (max-width: 1000px) {
}
</style>

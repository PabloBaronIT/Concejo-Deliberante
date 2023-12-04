<template>
  <div class="text-center contenedor">
    <div class="row">
      <div class="col" v-for="(item, index) in this.datos" :key="index">
        <div class="tarjeta">
          <h4>{{ item.titulo }}</h4>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col" v-for="(item, index) in this.datos2" :key="index">
        <div class="tarjeta2">
          <h4>{{ item.titulo }}</h4>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "GrillaComponent",
  data() {
    return {
      datos: [
        { titulo: "COLABORACIÓN CIUDADANA" },
        { titulo: "CONCURSOS PÚBLICOS" },
        { titulo: "DEFENSOR CIUDADANO" },
      ],
      datos2: [
        { titulo: "CONCEJALES" },
        { titulo: "ORDENANZAS" },
        { titulo: "EVENTOS" },
        { titulo: "GALERÍA" },
      ],
    };
  },
};
</script>
<style scoped>
.contenedor {
  width: 90%;
  margin: auto;
  gap: 2rem;
}
.tarjeta {
  width: 100%;
  height: 20vh;
  border-radius: 20px;
  background: linear-gradient(90deg, #e52320 0.25%, #ffcc03 104.39%);
  padding: 1.5rem 5rem;
}
.tarjeta2 {
  width: 100%;
  height: 20vh;
  border-radius: 20px;
  padding: 2.5rem 3rem;
  background: linear-gradient(271deg, #e52320 -13.11%, #ffcc03 128.45%);
  margin-top: 2rem;
}
h4 {
  color: white;
  font-weight: 900;
  font-size: 30px;
}
@media (max-width: 800px) {
  .tarjeta {
    margin-top: 2rem;
  }
}
@media (max-width: 1200px) {
  .tarjeta {
    margin-top: 2rem;
  }
}
</style>

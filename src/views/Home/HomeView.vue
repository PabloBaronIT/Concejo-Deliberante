<template>
  <ImagenComponent />
  <div class="texto">
    <h4>
      Te damos la bienvenida al portal oficial del Concejo Deliberante (CD) de
      Sacanta. Cada representante en este cuerpo <br />legislativo refleja las
      diversas fuerzas políticas elegidas por la comunidad, expresando así una
      variedad de concepciones sobre las funciones del Estado.
    </h4>
  </div>
  <TarjetasComponent />
  <div class="descubri">
    <h4>DESCUBRÍ</h4>
  </div>
  <GrillaComponent />
  <div class="descubri">
    <h4>NOTICIAS DESTACADAS</h4>
  </div>
  <CarouselComponent />
</template>

<script>
// @ is an alias to /src
import ImagenComponent from "@/components/Imagen/ImagenComponent.vue";
import TarjetasComponent from "@/components/Tarjetas/TarjetasComponent.vue";
import CarouselComponent from "@/components/Carousel/CarouselComponent.vue";
import GrillaComponent from "@/components/Grilla/GrillaComponent.vue";
export default {
  name: "HomeView",
  components: {
    ImagenComponent,
    TarjetasComponent,
    CarouselComponent,
    GrillaComponent,
  },
};
</script>
<style scoped>
.texto {
  text-align: center;
  width: 88vw;
  margin: auto;
  margin-top: 2rem;
  /* color: #4b4a49; */
}
h4 {
  font-size: 23px;
  font-weight: 700;
  line-height: normal;
  color: #4b4a49;
}
.descubri {
  text-align: center;
  margin-top: 4rem;
  margin-bottom: 1rem;
}
@media (max-width: 800px) {
  .texto {
    margin-top: -10rem;
    width: 100%;
  }
}
@media (max-width: 1000px) {
  .texto {
    margin-top: -5rem;
    width: 90%;
  }
}
@media (max-width: 1200px) {
  .texto {
    margin-top: -2rem;
  }
}
</style>

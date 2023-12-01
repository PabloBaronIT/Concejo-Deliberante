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
</template>

<script>
// @ is an alias to /src
import ImagenComponent from "@/components/Imagen/ImagenComponent.vue";
export default {
  name: "HomeView",
  components: {
    ImagenComponent,
  },
};
</script>
<style scoped>
.texto {
  text-align: center;
  width: 88vw;
  margin: auto;
  margin-top: 2.5rem;
  color: #4b4a49;
}
h4 {
  font-size: 23px;
  font-weight: 700;
  line-height: normal;
}
</style>

<template>
  <div class="contenedor">
    <div class="tarjeta">
      <img src="@/assets/images/Engranaje.svg" alt="" />
      <h5>FUNCIÓN</h5>
      <h5 style="font-weight: 400">
        Como Poder Legislativo de la ciudad de Sacanta, tiene la función de
        proponer y aprobar ordenanzas que sirvan para mejorar la calidad de vida
        de la ciudadanía, en pos del bien común. Además, controla y fiscaliza
        las acciones del Poder Ejecutivo Municipal.
      </h5>
    </div>
    <div class="tarjeta">
      <img src="@/assets/images/Personas.svg" alt="" />
      <h5>CONCEJALES</h5>
      <h5 style="font-weight: 400">
        Son quienes representan a las vecinas y vecinos de la ciudad de Sacanta
        dentro del Concejo Deliberante, donde se debaten y aprueban todos los
        proyectos que son presentados.
      </h5>
    </div>
    <div class="tarjeta">
      <img src="@/assets/images/Ordenanza.svg" alt="" />
      <h5>ORDENANZAS</h5>
      <h5 style="font-weight: 400">
        Contiene todas las normativas aprobadas por el CD que se encuentran
        vigentes. Su publicación y ordenamiento es fundamental para garantizar
        el acceso a la información pública y la seguridad jurídica.
      </h5>
    </div>
  </div>
</template>
<script>
export default {
  name: "TrajetasComponent",
};
</script>
<style scoped>
.contenedor {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  width: 88%;
  margin: auto;
  margin-top: 5vh;
}
.tarjeta {
  width: 32%;
  min-height: 58vh;
  background: #fff;
  border-radius: 0px 30px;
  text-align: center;
  padding: 1.5rem 1rem;
}
.tarjeta h5 {
  font-weight: 600;
  color: #4b4a49;
  line-height: normal;
}
@media (max-width: 800px) {
  .contenedor {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    height: auto;
  }
  .tarjeta {
    width: 60%;
    margin-top: 2rem;
  }
}
/* @media (max-width: 800px) {
  .contenedor {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    height: auto;
  }
  .tarjeta {
    width: 60%;
    margin-top: 2rem;
  }
} */
</style>

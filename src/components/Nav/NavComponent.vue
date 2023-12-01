<template>
  <nav class="top-nav-container">
    <router-link to="/"
      ><img src="@/assets/images/LogoSacantaRojo.svg" alt="" class="logo-muni"
    /></router-link>

    <div class="buscador">
      <BuscadorComponent />
      <div class="redes-container">
        <a href="">
          <img class="redes" src="@/assets/images/Email.svg" alt="" />
        </a>
        <a href="">
          <img class="redes" src="@/assets/images/Instagram.svg" alt="" />
        </a>
        <a href="">
          <img class="redes" src="@/assets/images/Facebook.svg" alt="" />
        </a>
      </div>
    </div>
    <div class="nav-botones">
      <div class="dropdown">
        <button
          class="btn btn"
          type="button"
          data-bs-toggle="dropdown"
          aria-expanded="false"
        >
          EL CONCEJO
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button
          class="btn btn"
          type="button"
          data-bs-toggle="dropdown"
          aria-expanded="false"
        >
          LEGISLACIÓN
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button
          class="btn btn asd"
          type="button"
          data-bs-toggle="dropdown"
          aria-expanded="false"
        >
          NOVEDADES
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button
          class="btn btn"
          type="button"
          data-bs-toggle="dropdown"
          aria-expanded="false"
        >
          CIUDADANÍA
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button
          class="btn btn"
          type="button"
          data-bs-toggle="dropdown"
          aria-expanded="false"
        >
          CONTACTO
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
import BuscadorComponent from "@/components/Buscador/BuscadorComponent.vue";
export default {
  name: "NavComponent",
  components: {
    BuscadorComponent,
  },
};
</script>

<style>
.logo-muni {
  width: 180px;
}
</style>
<style scoped>
.top-nav-container {
  height: 15vh;
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
  align-items: center;
  padding: 2%;
  position: fixed;
  width: 100%;
  padding: 0 6rem;
  position: relative;
}

.redes {
  max-width: 40px;
}
.buscador {
  width: 38vw;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.redes-container {
  display: flex;
  width: 9vw;
  justify-content: space-between;
  /* margin-right: 3rem; */
}
.nav-botones {
  width: 86vw;
  height: 7vh;
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-around;
  align-items: center;
  bottom: -2.8rem;
  z-index: 5;
  position: absolute;
  background: linear-gradient(90deg, #e52320 0.01%, #ffcc03 104.96%);
  border-radius: 0px 0px 15px 15px;
  /* margin-left: 12rem; */
  padding: 0 8rem;
}
.btn {
  color: white;
  font-size: 20px;
  font-weight: 700;
  /* width: 10vw; */
  /* background: red; */
}
.btn:hover {
  color: #4b4a49;
}
</style>

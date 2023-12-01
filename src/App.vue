<template>
  <NavComponent />
  <router-view />
  <FooterComponent />
</template>
<script>
import NavComponent from "@/components/Nav/NavComponent.vue";
import FooterComponent from "@/components/Footer/FooterComponent.vue";
export default {
  components: {
    NavComponent,
    FooterComponent,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50; */
  font-family: "Source Sans 3", sans-serif;
}
</style>

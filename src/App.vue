<template>
  <NavComponent />
  <router-view />
</template>
<script>
import NavComponent from "@/components/Nav/NavComponent.vue";
export default {
  components: {
    NavComponent,
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

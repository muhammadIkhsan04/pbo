<template>
  <div id="app" class="container">
    <navigasi />

    <router-view />
  </div>
</template>

<script>
import navigasi from "./components/navigasi.vue";
import NewArrival from "./components/NewArrival.vue";
export default {
  components: {
    navigasi,
    NewArrival,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

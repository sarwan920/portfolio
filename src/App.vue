<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Navigation />
    <About />
    <Portfolio />
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import About from "./components/About.vue";
import Portfolio from "./components/Portfolio.vue";

export default {
  name: "App",
  components: {
    Navigation,
    About,
    Portfolio,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Calligraffitti&family=Stardos+Stencil&display=swap');

* {
  box-sizing: border-box;
  background-color: #00022E;
 font-family: 'Stardos Stencil', cursive;


}


</style>

<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Navigation />

    <IntroCard />

    <About />

    <Skills />

    <Portfolio />
    
    <Footer />
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import About from "./components/About.vue";
import Skills from "./components/Skills.vue";
import Portfolio from "./components/Portfolio.vue";
import Footer from "./components/Footer.vue";
import IntroCard from "./components/IntroCard.vue";

export default {
  name: "App",
  components: {
    Navigation,
    About,
    Portfolio,
    Skills,
    Footer,
    IntroCard,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Calligraffitti&family=Stardos+Stencil&display=swap');

* {
  box-sizing: border-box;
  background-color: #eeeeee;
 font-family: 'Stardos Stencil', cursive;
 margin:0;
 padding:0;
 color: #222831;


}

.section__heading{
  color: #222831;
  transition: all 0.3s ease 0s;
  width:100%;
  cursor: pointer;
  text-align: center;
  }

.section__heading:hover{
    color: #0F9B8E;
}

/* body{
  min-height: 100vh;
  display: flex;
  flex-direction: column;
} */




.container{
  /* text-align:center; */
  padding: 30px 10%;
  
}



@media only screen and (max-width: 480px) {
 
 .section__heading{
   width: 100%;
 }
}


</style>

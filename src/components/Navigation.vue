<template>
  <div>
    <header>
      <a class="navbar-brand" href="#">SARWAN</a>
      <nav>
        <ul class="nav__links">
          <li><a href="">About</a></li>
          <li><a href="">Portfolio</a></li>
          <li><a href="">Contact</a></li>
        </ul>
      </nav>
      <!-- <div class="burger__container" @click.prevent="myFunction">
        <div class="bar1"></div>
        <div class="bar2"></div>
        <div class="bar3"></div>
      </div> -->
    </header>
  </div>
</template>

<script>
export default {
  // props: {
  //   msg: String
  // }

  methods(){
    return{

 myFunction(x) {
  x.classList.toggle("change");
  }


    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*Navigation CSS*/
li,
a {
  font-weight: 500;
  font-size: 20px;
  color: #222831;
  text-decoration: none;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 30px 10%;
}

.nav__links {
  list-style: none;
}

.nav__links li {
  display: inline-block;
  padding: 0 20px;
}

.nav__links li a {
  transition: all 0.3s ease 0s;
}

.nav__links li a:hover {
  color: #0f9b8e;
}

.navbar-brand {
  cursor: pointer;
  font-weight: bold;
  font-size: 30px;
  transition: all 0.3s ease 0s;
  font-family: "Calligraffitti", cursive;
}

.navbar-brand:hover {
  color: #0f9b8e;
}
/*Navigation CSS ENDS */

/**Navigation BurgerContainer starts here*/
/* .burger__container {
  display: none;
  cursor: pointer;
}

.bar1,
.bar2,
.bar3 {
  width: 35px;
  height: 5px;
  background-color: #333;
  margin: 6px 0;
  transition: 0.4s;
}

.change .bar1 {
  -webkit-transform: rotate(-45deg) translate(-9px, 6px);
  transform: rotate(-45deg) translate(-9px, 6px);
}

.change .bar2 {
  opacity: 0;
}

.change .bar3 {
  -webkit-transform: rotate(45deg) translate(-8px, -8px);
  transform: rotate(45deg) translate(-8px, -8px);
} */
/**Navigation BurgerContainer ends here*/

/**Navigation Responsive CSS starts here*/
/* @media only screen and (max-width: 480px) {
  nav {
    display: none;
  }

  .burger__container {
    display: inline-block;
  }
} */

/**Navigation Responsive CSS Ends here*/
</style>

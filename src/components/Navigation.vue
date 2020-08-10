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
    </header>
  </div>
</template>

<script>
export default {
  // props: {
  //   msg: String
  // }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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

.nav__links li{
  display: inline-block;
  padding: 0 20px;
}

.nav__links li a{
  transition: all 0.3s ease 0s;
}

.nav__links li a:hover{
  color: #0F9B8E;
}

.navbar-brand {
  cursor: pointer;
  font-weight: bold;
  font-size:30px;
  transition: all 0.3s ease 0s;
 font-family: 'Calligraffitti', cursive;
  
}

.navbar-brand:hover{
  color: #0F9B8E;
}
</style>

<template>
  <div>
    <section class="container">
      <h1 class="section__heading">
        Skills
      </h1>
      <ul>
        <li><img src="https://img.icons8.com/color/48/000000/vue-js.png" /><h5>VUE JS</h5></li>
        <li><img src="https://img.icons8.com/color/48/000000/html-5.png"/><h5>HTML</h5></li>
        <li><img src="https://img.icons8.com/color/48/000000/css3.png"/><h5>CSS</h5></li>
        <li><img src="https://img.icons8.com/color/48/000000/javascript-logo-1.png"/><h5>JAVASCRIPT</h5></li>
        <li><img src="https://img.icons8.com/color/48/000000/nodejs.png"/><h5>NODE JS</h5></li>
        <li><img src="https://img.icons8.com/color/48/000000/bootstrap.png"/><h5>BOOTSTRAP</h5></li>
        <li><img src="https://img.icons8.com/fluent/48/000000/database.png"/><h5>MYSQL</h5></li>
           <li><img src="https://img.icons8.com/color/48/000000/mongodb.png"/><h5>MONGODB</h5></li>
     
      </ul>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      skills: ["HTML", "CSS", "JAVASCRIPT", "NODE JS", "VUE JS"],
    };
  },
};
</script>

<style scoped>
ul {
  display: grid;
  grid-template-columns: 25% 25% 25% 25%;
  align-content: space-between;
  text-align: center;
}

ul li {
  list-style: none;
  margin: 20px 20px;
  cursor: pointer;
  /* justify-content: center; */
}



ul li:hover {
  transform :scale(1.1);
  transition:0.3s;
  
}




@media only screen and (max-width: 480px) {
 
 ul {
  display: grid;
  grid-template-columns: 50% 50%;
  align-content: space-between;
  text-align: center;
}


}
</style>

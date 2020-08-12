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
  display: flex;
  align-content: space-between;
  text-align: center;
}

ul li {
  list-style: none;
  margin: 20px;
  /* justify-content: center; */
}
</style>

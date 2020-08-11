<template>
  <div>
    <section class="container">
      <h1 class="section__heading">My Portfolio</h1>
      <div class="card__container">
        <div class="card" v-for="test in tests" v-bind:key="test">
          <img
            src="https://api.time.com/wp-content/uploads/2019/08/better-smartphone-photos.jpg"
            alt="Avatar"
            style="width:100%"
          />
          <div class="container">
            <h4><b>John Doe</b></h4>
            <p>Architect Engineer</p>
            <a href="#" class="btn btn-primary">Go Live</a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tests: [1, 2, 2, 2],
    };
  },
};
</script>

<style scoped>
 .card {
/*Add shadows to create the "card" effect*/ 
  /* border-radius: 10px; */
  width: 18rem;
  /* box-shadow: 0 4px 8px 0 rgba(15, 155, 141, 1); */
   box-shadow: 0 1px 3px rgba(15, 155, 141, 0.12), 0 1px 2px rgba(15, 155, 141, 0.24);
  transition: all 0.3s cubic-bezier(.25,.8,.25,1);
  transition: 0.3s;
  margin: 10px 0;
  
}



/* On mouse-over, add a deeper shadow */
 .card:hover {
  /* box-shadow: 0 8px 8px 0 #0f9b8d; */
  box-shadow: 0 14px 28px rgba(15, 155, 141, 0.25), 0 10px 10px rgba(15, 155, 141, 0.22);
} 





.card__container {
  display: grid;
  grid-template-columns: 25% 25% 25% 25%;

  /* grid-template-columns: 50% 50%; */
}

/* Add some padding inside the card container */
/* .container {
  padding: 2px 16px;
} */

.btn {
  display: inline-block;
  font-weight: 400;
  color: #212529;
  text-align: center;
  vertical-align: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  background-color: transparent;
  border: 1px solid transparent;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out,
    border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

.btn-primary {
  color: #fff;
  background-color: #0f9b8e;
  border-color: #0f9b8e;
}

.btn-primary:hover {
  color: #fff;
  background-color: #0e8377;
  border-color: #0e8377;
}

a {
  text-decoration: none;
}


@media only screen and (max-width: 480px) {
 
 .card__container {
  display: grid;
  /* grid-template-columns: 25% 25% 25% 25%; */

  grid-template-columns: 100%;
  justify-content: center;
}


.card {
  /* Add shadows to create the "card" effect */
  width: 18rem;
  box-shadow: 0 4px 8px 0 #0f9b8e;
  transition: 0.3s;
  margin: 20px 0px;
}

}




</style>

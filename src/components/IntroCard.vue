<template>
<div class="container">
<div class="card">
  <img src="https://firebasestorage.googleapis.com/v0/b/student-developer-club.appspot.com/o/members%20pix%2Fsarwan.png?alt=media&token=14614ad5-b022-470a-95a7-ab34418f9c0c" alt="John" style="width:50%">
  <h1>Sarwan Nizamani</h1>
  <p class="title">Full Stack Web Developer</p>
  <p>University of Sindh, Jamshoro</p>
  <a href="#"><i class="fa fa-github"></i></a>
  <a href="#"><i class="fa fa-twitter"></i></a>
  <a href="#"><i class="fa fa-linkedin"></i></a>
  <a href="#"><i class="fa fa-facebook"></i></a>
  <!-- <p><button>Contact</button></p> -->

  <a href="#" class="button">Contact</a>
</div>
</div>
  
</template>

<script>
export default {

}
</script>

<style scoped>

.card {
  /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); */
  max-width: 40%;
  margin: auto;
  text-align: center;
}

.title {
  color: grey;
  font-size: 18px;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 10px;
  color: rgb(12, 1, 1);
  background-color: #0F9B8E;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
  margin: 5px;
}

button:hover, a:hover {
  opacity: 0.7;
  /* background-color: #0d7469; */
}

i{
     color: #0F9B8E;
}

</style>
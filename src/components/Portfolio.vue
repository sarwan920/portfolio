<template>
  <div>
    <section class="container">
      <h1 class="section__heading">My Portfolio</h1>
      <div class="card__container">
        <div
          v-for="test in tests"
          v-bind:key="test"
          class="card"
          style="width: 18rem;"
        >
          <img
            class="card-img-top"
            src="https://i.ytimg.com/vi/EoHQtXNVKH8/maxresdefault.jpg"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
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
      tests: [1, 2,2,2,4,]
    };
  },
};
</script>

<style scoped>
.card {
  position: relative;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-direction: column;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: 2px solid rgba(0, 0, 0, 0.125);
  border-radius: 0.25rem;
  margin:1rem;
}

.card__container{
  display:flex;
  flex-direction: row;
  
}

.card-img-top {
  -ms-flex-negative: 0;
  flex-shrink: 0;
  width: 100%;
}

.card-body {
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  min-height: 1px;
  padding: 1.25rem;
}

.card-title {
  margin-bottom: 0.75rem;
}

.card-text:last-child {
  margin-bottom: 0;
}

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
</style>

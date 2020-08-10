<template>
  <div>
    <section class="container">
      <h1 class="section__heading">
        Skills
      </h1>
      <ul>
        <li v-for="skill in skills" v-bind:key="skill">{{skill}}</li>
      </ul>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      skills: ["HTML", "CSS","JAVASCRIPT" ,"NODE JS", "VUE JS"],
    };
  },
};
</script>

<style scoped>
ul li {
  list-style: none;
}
</style>

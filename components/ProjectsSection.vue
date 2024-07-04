<template>
  <section class="projects">
    <h2>My Projects</h2>
    Here's some of my projects:

    <div class="card" style="width: 40rem;">
    <img class="card-img-top" src="/assets/logo.png" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
  </section>

</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 0;
  background: #e9ecef;
}
</style>

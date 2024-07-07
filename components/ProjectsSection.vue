<template>
  <section class="projects">
    <h2 class="text-light">My Projects</h2>
    <p class="mb-4 text-light">Here's some of my projects:</p>
    
      <div class="row">
        <div class="col-md-5 mb-4">
          <div class="card" style="width: 32rem;">
            <img class="card-img-top border border-white" src="/assets/logo.png" alt="Top-up in">
            <div class="card-body">
              <h5 class="card-title">Top-up in Website</h5>
              <p class="card-text">This Website is my team's projects for the Final Project. You can click this button below to the further information</p>
              <a href="https://github.com/ZumaAkbarID/SiPPOB" target="_blank" class="btn btn-primary">Click Here</a>
            </div>
          </div>
        </div>
        <div class="col-md-7 mb-4">
          <div class="card" style="width: 30rem;">
            <img class="card-img-bottom border border-white" src="/assets/loremipsum.png" alt="Top-up in">
            <div class="card-body">
              <h5 class="card-title">Example of different projects</h5>
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. You can click this button below to the further information</p>
              <a href="https://github.com/ZumaAkbarID/SiPPOB" target="_blank" class="btn btn-primary">Click Here</a>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 mb-4">
          <div class="card mt-5" style="width: 32rem;">
            <img class="card-img-top border border-white" src="/assets/loremipsum.png" alt="Top-up in">
            <div class="card-body">
              <h5 class="card-title">Example of different projects</h5>
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. You can click this button below to the further information</p>
              <a href="https://github.com/ZumaAkbarID/SiPPOB" target="_blank" class="btn btn-primary">Click Here</a>
            </div>
          </div>
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
  padding: 50px;
  background: linear-gradient(50deg, #393b50, #5383d5);
  }
</style>

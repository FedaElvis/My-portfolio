<template>
  <section id="portfolio" class="sect2">
    <h5 class="service">PORTFOLIO</h5>
    <H3>MY LATEST PROJECTS</H3>
    <h3>These are the some of my latest projects. some links are not included due to NDA but you can contact me for more.</h3>
  </section>

  <section class="projects">
    <div class="project"></div>
    <div class="project"></div>
    <div class="project"></div>
    <div class="project"></div>
    div
  </section>
</template>

<script setup>

</script>

<style scope>
.sect2 {
  margin-top: 150px;
  color: white;
  text-align: center;
  padding: 0 30px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
.service {
  color: #34d399;
  font-weight: bold;
  font-size: large;
}

.projects{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}

.project{
  border-radius: 4px;
    height: 200px;
    width: 300px;
    background-color: rgba(250, 244, 244, 0.815);
    margin: 20px;
}

h3{
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

@media only screen and (max-width: 640px) {
  .projects{
    align-items: center;
    justify-content: center;
  }
  }
</style>
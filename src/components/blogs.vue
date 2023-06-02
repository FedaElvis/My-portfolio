<template>
   <section id="blog" class="sect2">
    <h5 class="service">BLOGS</h5>
    <H3>My Latest Blogs</H3>
    <h3>I have begun my journey of blog writing just wait for it.</h3>
  </section>

  <!-- <section class="projects">
    <div class="project"></div>
    <div class="project"></div>
    <div class="project"></div>
  </section> -->
</template>

<script setup>



</script>

<style scoped>
.sect2 {
  margin-top: 100px;
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
    justify-content: space-between;
}

.project{
    height: 200px;
    width: 300px;
    background-color: rgb(252, 252, 252);
    border-radius: 50%;
    margin: 20px;
}
h3{
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
}
</style>
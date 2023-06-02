<template>
  <Navigation></Navigation>
  <Introduction></Introduction>
  <FirstView></FirstView>
  <Ntab></Ntab>
  <projects></projects>
  <blogs></blogs>
  <contact></contact>
  <!-- <background></background> -->
</template>

<script setup>
import Navigation from "./components/Navigation.vue"
import Introduction from "./components/Introduction.vue"
import FirstView from  "./components/FirstView.vue"
import Ntab from "./components/Ntab.vue"
import projects from "./components/projects.vue"
import blogs from "./components/blogs.vue"
import contact from "./components/contact.vue"
</script>

<style>
* {
  
  box-sizing: border-box;
  /* background-color: #1E2235; */
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  
}

body{
  background-color: #1E2235;
}

</style>
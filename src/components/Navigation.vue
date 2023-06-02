<template>
  <div class="content">
    <nav>
      <div class="header">
        <h2 class="first-el">Feda Elvis</h2>
      </div>

      <div class="mobile-menu" @click="showMenu">
        <template v-if="!show">
          <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="white"
          width="35px"
          height="35px"
          aria-hidden="true"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          ></path>
        </svg>
        </template>
        <template v-if="show">
          <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="white"
          width="35px"
          height="35px"
          aria-hidden="true"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M6 18L18 6M6 6l12 12"
          ></path>
        </svg>
        </template>
      </div>
      <div class="menu" :class="show ? 'displayMenu' : ''">
        <a href="#Home" class="btns">
          <li>Home</li>
        </a>
        <a href="#service" class="btns">
          <li>Services</li>
        </a>
        <a href="#skills" class="btns">
          <li>Skills</li>
        </a>
        <a href="#portfolio" class="btns">
          <li>Portfolio</li>
        </a>

        <a href="#blog" class="btns">
          <li>Blog</li>
        </a>
        <a href="#contacts" class="btns">
          <li>Contact</li>
        </a>
      </div>
    </nav>
  </div>
  
</template>

<script setup>
import { ref } from "vue";
let show = ref(false);
function showMenu() {
  show.value = !show.value;
}
</script>

<style scoped>
*{
  box-sizing: border-box;
}
nav {
  /* font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif; */
  display: flex;
  list-style: none;
  z-index: 1;
  justify-content: space-between;
  padding: 5px;
  padding-top: 0px;
  align-items: center;
  height: 70px;
  box-sizing: border-box;
  width: 100%;
  position: fixed ;
  top: 0;
  left: 0;
  background-color: #23273B;
}
.mobile-menu {
  display: none;
}

nav ul {
  float: right;
  margin-right: 20px;
}

.menu {
  flex: 1;
  display: flex;
  justify-content: end;
  align-items: baseline;
  background-color: #23273B;
}


a:hover{
  background: #34D399;
}

/*li {
  display: inline;
  line-height: 80px;
  margin: 0 5px;
  border-radius: 5px;
  
}*/

li{
  background-color: #23273B;
  margin: 0px;
  padding: 2px;
}

.btns:hover {
  transition: 0.5s;
  cursor: grab;
}


.first-el {
  color: rgb(233, 240, 245);
  font-weight: bolder;
  font-size: x-large;
  /* font-family: serif; */
  background-color: #23273B;
  margin: 0px;
  font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}



.btns {
  text-decoration: none;
  margin: 0 5px;
  padding: 10px;
  border-radius: 5px;
  background-color: #23273B;
  color: white;
  /*font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;*/
}
.second-el {
  background-color: #34d399;
  font-size: larger;
  margin: 0px;
  border-radius: 0.25rem;
  box-sizing: border-box;
  display: inline;
  border: 0, solid;
  /* padding-top: 00.25rem;
    padding-bottom: 00.25rem;*/
  max-width: 100%;
  /* font-family: cursive; */
  color: black;
  /* height: 100%;
    width: 100%;*/
}

@media only screen and (max-width: 640px) {
  .menu {
    position: absolute;
    width: 300px;
    /* height: 400px; */
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-items: flex-start;
    left: 0;
    top: 60px;
    transform: translate(-300px,0);
    transition: transform 0.3s;
    background-color: #23273B;
  }

  a {
    background-color: #23273B;
    text-decoration: none;
  }

  li {
    width: 100%;
    height: 40px;
    padding-left: 50px;
    /* background-color: red; */
    display: flex;
    align-items: center;
    /* justify-content: center; */
  }

  .mobile-menu {
    display: block;
  }

  .displayMenu {
    transform: translate(0, 0);
    transition: tranform 0.43s;
  }

  .btns {
    width: 100%;
    
  }

  .btns:hover {
  color: green;
  transition: 0.5s;
  cursor: grab;
   
}
}
</style>

<template>
  <section id="service" class="sect2">
    <h5 class="service">SERVICES</h5>
    <H3>WHAT I OFFER</H3>
    <h3>i develop web and mobile apps for all platforms</h3>
  </section>

  <section class="sect3">
    <div class="second-img">
      <!-- <img src="images/web.svg.svg"  alt="logo" /> -->
      <LogoWeb style="color:lightgreen; height:50px;"></LogoWeb>
      <div class="desc">
        <h2 class="hh2">Web App Development</h2>
        <h4 >
          I develop both backend and frontend development anything relating to web
        </h4>
      </div>
    </div>
    <div class="second-img">
      <!-- <img src="images/vue.svg.svg" alt="logo" /> -->
      <PhoneIcon style="color:lightgreen; height:50px;"></PhoneIcon>
      <div class="desc">
        <h2 class="hh2">Mobile App Development</h2>
        <h4 class="hh4">
          I develop both hybrid and native mobile applications for android and ios
        </h4>
      </div>
    </div>
    <div class="second-img">
      <!-- <img src="images/vue.svg.svg" alt="logo" /> -->
      <Desktop style="color:lightgreen; height:50px;"></Desktop>
      <div class="desc">
        <h2 class="hh2">Desktop App Development</h2>
        <h4 class="hh4">
          I develop desktop applications for windows in C# or hybrid in
          electron.js
        </h4>
      </div>
    </div>
  </section>

  <section id="skills">
     <section class="sect4">
      <h2 class="skills">SKILLS</h2>
      <H3 class="staff">THE STAFF I WORK WITH</H3>
      </section>
    </section>
      
      <!-- <div class="first-span"> 
        <button class="span1">Highlight</button>
        <button class="span2" id="span2">Frontend</button>
        <button class="span2">Backend</button>
        <button class="span2">Fullstack</button>
      </div> 
 <n-button type="primary">Primary</n-button> 
      
    <div class="skills"> 
      <div>Highlight</div>
      <div>Frontend</div>
      <div>Baackend</div>
      <div>Fullstack</div>
    </div>
  
  <div class="my-images">
      <div>
        <p  class="texts">VUE.JS</p>
        <img src="./images/structure.png" height="50px" width="" alt="hdhd">
      </div>
      <div>
        <p class="texts">SASS</p>
        <img src="./images/sass.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">TYPESCRIPT</p>
        <img src="./images/typescript.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">PHP</p>
        <img src="./images/php.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">JAVA</p>
        <img src="./images/java.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">HTML5</p>
        <img src="./images/html-5.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">TAILWIND</p>
        <img src="./images/flag.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">C#</p>
        <img src="./images/c-sharp.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">C++</p>
        <img src="./images/c-logo.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">CSS</p>
        <img src="./images/css-3.png" height="50px" alt="">
      </div>
      <div>
        <p class="texts">FLUTTER</p>
        <img src="./images/flutter.svg" height="50px" alt="">
      </div>
      <div>
        <p class="texts">POSTGREQSL</p>
        <img src="./images/postgresql.svg" height="50px" alt="">
      </div>

      <div>
        <p class="texts">LARAVEL</p>
        <img src="./images/laravel.svg" height="50px" alt="">
      </div>
    </div>

    <section id="service" class="sect2">
    <h5 class="service">PORTFOLIO</h5>
    <H3>My Latest Projects </H3>
    <h4>These are the some of my latest projects. some links are not included due to NDA but you can contact me for more.</h4>
  </section>

  <section id="service" class="sect2">
    <h5 class="service">CONTACT</h5>
    <H3>Check me out </H3>
    
   </section> 
   -->
</template>

<script setup>
import { NButton } from "naive-ui"
import {
  PhonePortraitOutline as PhoneIcon,
  LogoWebComponent as LogoWeb,
  DesktopOutline as Desktop,
} from "@vicons/ionicons5"

</script>

<style scoped>
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

.sect3 {
  display: flex;
  /* align-items: center; */
  justify-content: space-evenly;
  color: white;
  margin-bottom: 100px;
  flex-wrap: wrap;
}

.second-img {
  background-color: #23273b;
  border-radius: 3%;
  /* border: 2px solid #2d3146; */
  text-align: start;
  /* font-weight: bold; */
  width: 350px;
  margin-top: 20px;
  border: none;
  outline: none;
  padding: 50px ;
}
#skills {
  display: flex;
  align-items: center;
  justify-content: center;
  color: #34d399;
  /* font-weight: bold; */
  /* font-size: large; */
  margin-top: 60px;
  margin-bottom: 30px;
}

.staff {
  color: white;
}

.first-span {
  display: inline-flex;
}
.span1 {
  background-color: #d1d5db;
  color: green;
  font-size: x-large;
  padding-top: 10px;
  padding-bottom: 10px;
  border: none;
  outline: none;
  border-radius: 25px 0 0 25px;
}
.span2 {
  background-color: #d1d5db;
  font-size: x-large;
  padding-top: 10px;
  padding-bottom: 10px;
  color: rgb(71, 57, 57);
  outline: none;
  border: none;
  border-radius: 0 0 0 0 0 0 0 0 25px;
}



.desc h2, h4 {
  background-color: #23273b;
  margin: 0;
}

h4 {
  padding-top: 15px;
}

.sect4 {
  text-align: center;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

.my-images{
  margin-top: 40px;
  justify-content: space-between;
    display: flex;
    padding: 0 30px;
}

.texts{
  color: #fff;
  font-family: monospace;
  opacity: 10px;
}

.skills, .skills div {
  display: flex;
  justify-content: center;
  max-width: 600px;
  /* background-color: #d1d5db; */
  height: 50px;
  align-items: center;
  border-radius: 10px;
}

@media only screen and (max-width: 640px) {
  .second-img {
    padding: 30px
  }

  /* .main-img {
    align-items: center;
    justify-content: center;
  } */

  /* .sect3 {
    flex-direction: column;
    display: flex;
    width: 100%;
  } */

  /* .my-images{
        display: flex;
        flex-direction: column;
    } */
}
</style>


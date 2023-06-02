<template>
    <n-tabs type="segment" class="segments">

      <n-tab-pane name="oasis" tab="FONT END" class="rule">
        <div class="my-images">
          <div>
        <p  class="texts">VUE.JS</p>
        <img src="./images/c-sharp.png" alt="" style="height:50px;">
      </div>
      <div>
        <p class="texts">SASS</p>
        <img src="./images/sass.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">TYPESCRIPT</p>
        <img src="./images/typescript.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">PHP</p>
        <img src="./images/php.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">JAVA</p>
        <img src="./images/java.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">HTML5</p>
        <img src="./images/html-5.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">TAILWIND</p>
        <img src="./images/flag.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">C#</p>
        <img src="./images/c-sharp.png" style="height:50px;" alt="">
      </div>
      </div>
      </n-tab-pane>

      <n-tab-pane name="the beatles" tab="BACK END">
        <DIV class="my-images">
          <div>
        <p class="texts">CSS</p>
        <img src="./images/css-3.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">FLUTTER</p>
        <img src="./images/flutter.svg" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">POSTGREQSL</p>
        <img src="./images/postgresql.svg" style="height:50px;" alt="">
      </div>
        <div>
        <p class="texts">C++</p>
        <img src="./images/c-logo.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">CSS</p>
        <img src="./images/css-3.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">FLUTTER</p>
        <img src="./images/flutter.svg" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">POSTGREQSL</p>
        <img src="./images/postgresql.svg" style="height:50px;" alt="">
      </div>

      <div>
        <p class="texts">LARAVEL</p>
        <img src="./images/laravel.svg" style="height:50px;" alt="">
      </div>
    </DIV>
      </n-tab-pane>

      <n-tab-pane name="jay chou" tab="FULL STACK">
        <div class="my-images">
          <div>
        <p  class="texts">VUE.JS</p>
        <img src="./images/c-sharp.png" alt="" style="height:50px;">
      </div>
      <div>
        <p class="texts">SASS</p>
        <img src="./images/sass.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">TYPESCRIPT</p>
        <img src="./images/typescript.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">PHP</p>
        <img src="./images/php.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">JAVA</p>
        <img src="./images/java.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">HTML5</p>
        <img src="./images/html-5.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">TAILWIND</p>
        <img src="./images/flag.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">C#</p>
        <img src="./images/c-sharp.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">C++</p>
        <img src="./images/c-logo.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">CSS</p>
        <img src="./images/css-3.png" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">FLUTTER</p>
        <img src="./images/flutter.svg" style="height:50px;" alt="">
      </div>
      <div>
        <p class="texts">POSTGREQSL</p>
        <img src="./images/postgresql.svg" style="height:50px;" alt="">
      </div>

      <div>
        <p class="texts">LARAVEL</p>
        <img src="./images/laravel.svg" style="height:50px;" alt="">
      </div>
    </div>
      </n-tab-pane>
    </n-tabs>
  </template>

<script setup >
import { NTabs, NTabPane } from "naive-ui"

</script>

<style scoped>
.segments{
  color: white;
  
  
  
}

.my-images{
  margin-top: 40px;
  justify-content: space-around;
  display: flex;
  flex-wrap: wrap;
  width: 100vw;
  margin-right: auto;
  margin-left: -35%;
  max-width: 700px;
  gap: 20px;
}

.texts{
  color: #fff;
  font-family: monospace;
  opacity: 10px;
  align-items: center;
  display: flex;
  justify-content: center;
}

.n-tabs {
  max-width: 400px;
  margin-left: auto;
  margin-right: auto;
}


@media screen and (max-width: 640px) {
  .my-images {
    margin-left: -10%;
    gap: 10px;
  }
}

</style>
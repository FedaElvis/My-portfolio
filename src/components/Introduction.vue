<template>
  <div id="Home" class="container1">
    <div class="first-bk">
      <p class="second-el">Software Developer</p>
      <h1>I am Feda Elvis.</h1>
      <H2>I am a passionate software designer with 2+ years of experience.</H2>
      <h3>Accra - Ghana/Remote</h3>
      <button class="btn-1">My Portfolio</button>
      <button class="btn-2">MY CV</button>

      <div class="container2">
        <h1 class="date">2+</h1>
        <h3 class="t">years</h3>
        <h3 class="t">Experience</h3>
      </div>
    </div>
    <div class="main-img">
      <img src="./images/developer.svg" alt="" style="height: 350px" /><img />
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.container1 {
  background-color: #23273b;
  position: relative;
  padding: 40px;
  padding-left: 0px;
  flex-wrap: wrap;
  color: white;
  margin-top: 50px;
  margin-bottom: 100px;
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

.container2 {
  display: flex;
}
.t{
  color: #34d399;
}
.main-img {
  /* position: absolute; */
  right: 0;
  top: 0px;
}

.date{
  font-size: 40px;
  
}

.second-el {
  background-color: #34d399;
  font-size: 30px;
  padding: 10px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  /* margin: 0px; */
  /* margin-left: 30px; */
  border-radius: 0.25rem;
  /* box-sizing: border-box; */
  /* display: inline; */
  /* border: 0, solid; */
  /* padding-top: 00.25rem;
    padding-bottom: 00.25rem;*/
  max-width: 100%;
  font-family: cursive;
  color: black;
  /* height: 100%;
    width: 100%;*/
}

.btn-1 {
  color: white;
  background-color: aqua;
  font-weight: bold;
  font-size: 20px;
  /* padding-top: 00.25rem;
  padding-bottom: 00.25rem; */
  padding: 10px;
  background-color: #23263a;
  border: 4px solid green;
  /* border-style: ridge; */
  border-radius: 5px;
}

.btn-2 {
  color: rgb(7, 173, 7);
  font-weight: bold;
  /* padding-top: 00.25rem;
  padding-bottom: 00.25rem; */
  padding: 9px;
  background-color: #384a64;
  margin-left: 20px;
  border-radius: 10px;
  border: none;
  font-size: 20px;
}

.btn-2:hover{
opacity: 0.6;
}

.first-bk {
  margin-left: 30px;
}
.app-2 {
  background-color: #23273b;
}

@media only screen and (max-width: 640px) {
  .main-img {
    flex-direction: column;
  }
  .container1 {
    
  }
}
</style>

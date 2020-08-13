<template>
  <div >
  <nav class="navbar navbar-expand-lg navbar-light bg-light">

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">HOME</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">PELATIHAN</a>
        <li class="nav-item active">
        <a class="nav-link" href="#">FAQ</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">ABOUT US</a>
      <li class="nav-item">
        <a class="nav-link" href="#">KARIR</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Join Pemateri</button>
    </form>
 
  </div>
</nav>
    <HelloWorld msg=""/>
    <h1> Pelatihan </h1>
    <h2> Silahkan cari pelatihan,workshop,atau seminar yang anda minati</h2>
    <input type="text" v-model="search" placeholder="Cari pelatihan,workshop,seminar" />
    
    <img alt="Vue logo" src="./assets/Bitmap.png">
     <img alt="Vue logo" src="./assets/Bitmap (1).png">
      <img alt="Vue logo" src="./assets/Bitmap (2).png">

  </div>
  
  
</template>

<script>

import HelloWorld from './components/HelloWorld.vue'

export default {
  
  components: {
    HelloWorld

   
  }
}
  
</script>

<style>
body{
  background : #0A93FF;
}
h1 {
  text-align: center;
  color: #fff;
  margin-top: 20px;
  font-family: Avenir;
  font-style: normal;
  font-weight: 900;
  font-size: 53px;


}
h2 {
    font-family: sans-serif; 
  text-align: center;
  color: #fff;
  font-size: 16px;

}
input {
    font-family: sans-serif; 
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

header{

  width: 100vw;
  padding:10px; 
}
nav{
  background:#0A93FF;
  padding: 20px 0;
  font-size: 12px;
  margin-bottom: 40px;
  font-family: HelveticaNeue;
}

a{
  color:#fff;
  text-decoration:none;
  padding:6px 8px;
  border-radius:10px;
}
li{
  display: inline-block;
  margin: 0 10px;
}
ul{
  list-style-type:none;
  margin:0;
}
button{

  float: right;
}
img{
  width:350px;
  height:270px;
  object-fit: absolute; object-position: 50px 80%; 
  
}

input{
  
}
</style>

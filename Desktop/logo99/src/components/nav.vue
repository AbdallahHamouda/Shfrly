<template>
  <div class="hello">
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
        <div class="pompo">
  <a class="navbar-brand " href="/"><img src="../assets/logo99.png" alt="logo is not found"></a>
  </div>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link navit" href="/" >Home </a>
      </li>
      <li class="nav-item">
        <a class="nav-link navit" href="#Gallery">Gallery</a>
      </li>
      <li class="nav-item">
        <a class="nav-link navit" href="#about">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link navit" href="#contact">Contact</a>
      </li>
    </ul>
  </div>
</nav>
  </div>
</template>
<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');
a{
    img{
        width:80%;
        margin-left:6%;
    }
}
ul{
    margin-right:8%;
    li{
        margin:2%;
    }
}
nav{
    box-shadow: 5px 0px 5px 3px rgba(163, 163, 163, 0.438);
}
.navit{
    font-family: 'Poppins', sans-serif;
    font-weight: bold;
    font-size: 18px;
}
@media only screen and (max-width: 600px) {
.pompo{
   margin-left:27%;
}
}
@media only screen and (max-width: 320px) {
.pompo{
   margin-left:20%;
}
}
</style>
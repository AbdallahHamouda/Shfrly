<template>
    <div class="bgimg" id="home">
      <h1>Build an identity for your Brand</h1>
      <button type="button" @click="getdown" class="btn btn-outline-danger btn-lg rounded-pill px-3 py-4 down"><img src="../assets/caret-down.svg" alt="image is not found"></button>
    </div>
</template>
<script>
export default {
  methods:{
    getdown(){
      window.scrollBy(0,750)
    }
  }
}
</script>
<style lang="scss" scoped>
.bgimg {
  /* The image used */
  background-image: url("../assets/bgimg.jpg");

  /* Set a specific height */
  height: 800px;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
h1{
  color:black;
  position:absolute;
  top:300px;
  color:#FF4500;
  width:100%;
  left:2.5%;
  font-weight:bold;
}
.down{
  position:absolute;
  top:470px;
  left: 45%;
  border-radius:100%;
}
button{
  img{
    width:50px;
  }
}
@media only screen and (max-width: 600px) {
  .down{
  position:absolute;
  top:470px;
  left: 39%;
  border-radius:100%;
}
}
</style>
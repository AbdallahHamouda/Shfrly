<template>
    <div id="Gallery">
        <h2>Gallery</h2>
        <div class="grid-container">
            <div class="flex-1">
  <div class="grid-item"><img src="../assets/img-1.jpg" alt="image is not found"></div>
  <div class="grid-item"><img src="../assets/img-2.jpg" alt="image is not found"></div>
    </div>
            <div class="flex-1">
  <div class="grid-item"><img src="../assets/bgimg.jpg" alt="image is not found"></div>
  <div class="grid-item"><img src="../assets/img-4.jpg" alt="image is not found"></div>
    </div>
            <div class="flex-1">
  <div class="grid-item"><img src="../assets/img-5.jpg" alt="image is not found"></div>
  <div class="grid-item"><img src="../assets/img-6.jpg" alt="image is not found"></div>
    </div>
    </div>
    <div class="btncen">
    <button class="btn btn-outline-primary px-4 py-3 rounded-pill mycus">More...</button>
   </div>
    </div>
</template>
<style lang="scss" scoped>
*{
    margin: 0%;
    padding:0%;
}
h2{
    text-align: center;
    margin:3%;
}

.flex-1{
    display:flex;
    justify-content: space-around;
    align-items: center;
}
.grid-item{
    margin-left:10%;
    img{
        width:70%;
        margin:5%;
    }
}
.mycus{
    font-weight: bolder;
    font-size: 20px;
    margin:3%;
}
.btncen{
    display:flex;
    justify-content:center;
    align-items: center;
}
@media only screen and (max-width: 600px) {
    .flex-1{
    display:flex;
    justify-content:center;
    align-items: center;
    flex-direction: column;
}
.grid-item{
    img{
        width:80%;
        margin:2%;
    }
}
}
</style>
<template>
    <div id="about">
        <h2>About</h2>
        <div class="flexo">
        <img src="../assets/aboutimg.jpg" alt="image is not found">
        <p>Graphics designer and logo maker.
Freelancer ,
<br> ready to join any team.<br>
Contact 📥 us to get the best customized design at best rates.<br>
PayPal accepted..</p>
</div>
    </div>
</template>
<style lang="scss" scoped>
h2{
    text-align:center;
    color:white;
    font-size: 3.5rem;
    margin-top:5%;
    margin-bottom:3%;
    font-weight: bolder;
}
.flexo{
    display: flex;;
    justify-content: space-around;
    align-items: center;
    flex-direction: row-reverse;
    img{
        width:40%;
        height: 40%;
        margin-right:5%;
    }
    p{
        font-size: 2rem;
        font-weight: bold;
        color:white;
        margin-right:10%;
        margin-left:5%;
    }
}
div{
    background-color: #538bbe;
    padding-top:5%;
    padding-bottom:5%;
    }
    @media only screen and (max-width: 600px) {
        .flexo{
            flex-direction: column;
            img{
                width:80%;
            }
            p{
                margin-left: 7%;
            }
        }
    }
</style>
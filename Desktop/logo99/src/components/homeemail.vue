<template>
    <div id="contact">
        <h2>Contact</h2>
        <p v-if="loloh" class="success">Sent Successfully</p>
        <p v-if="!loloh" class="danger">Does not Sent Successfully</p>
        <form action="post">
        <input type="email" class="rounded-3" placeholder="E-mail" v-model="email" @keypress.enter.prevent="emailSubmit">
        <textarea name="textarea" id="ta" class="rounded-3" cols="50" rows="10" placeholder="your message"></textarea>
        <button class="btn btn-primary rounded-pill mt-3 px-4 py-3 fs-2 fw-bolder subs">Submit</button>
        </form>
    </div>
</template>
<script>
// import axios from 'axios'

export default {
  data () {
    return {
      loloh: false,
      email: ''
    }
  },
  // logo_art99@gmail.com
/*  methods: {
    emailSubmit () {
      this.loloh = true
      axios.post('https://expressblogbe.herokuapp.com/api/email', { email: this.email }).then(function (response) {
        if (response.status === 200) {
          console.log('if is working')
        } else {
          console.log('if is not working')
        }
      })
        .catch(function (error) {
          console.log(error)
        })
    }
  }*/
}
</script>
<style lang="scss" scoped>
h2{
text-align: center;
color: white;
margin-top:3%;
margin-bottom:3%;
}
div{
    background-color: black;
    margin-top:3%;
    padding:10%;
}
form{
    display:flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    input{
        width:40%;
        height:40px;
        margin:3%;
        }
    input::placeholder{
        color:rgb(44, 44, 44);
    }
}
.success{
  color:greenyellow;
  text-align:center
}
.danger{
  color:rgb(252, 81, 81);
  text-align:center
}
.subs{
  font-weight:bolder;
  font-size:1.2rem;
}
@media only screen and (max-width: 600px) {
form{
  input{
    width:70%;
  }
  textarea{
    width:85%;
  }
}
}
</style>

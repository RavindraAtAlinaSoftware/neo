<template>
  <div class="container">
    <div class="div">
      <img src="/images/back.png">
    </div>
    <div class="logo_container">
      <img class="logo" src="/images/logo.png" alt="">
    </div>

    <h4>Sign in</h4>
    <input class="input_control" type="text" id="name" placeholder="Username">
    <input class="input_control" type="password" id="password" placeholder="Password">
    <label id="rememberMeLabel">
      <input type="checkbox" id="rememberMe"> Stay logged in 
    </label>
    <button>Sign in</button>
    <div class="forget_password_container text-center">
      <a href="#">Forgot password?</a>
    </div>
  </div>
</template>
<script>
export default {}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:200,300,400&display=swap');
* {
  font-family: 'Montserrat', sans-serif;
}

.logo {
  width: 100%;
}

.logo_container {
  margin-top: 50px;;
  padding: 10px 0px 80px;
}

.text-center {
  text-align: center;
}

h4 {
  font-weight: 300;
  margin-bottom: 20px;
}

.input_control {
  outline: none;
  border-radius: 15px;
  font-size: 15px;
  font-weight: 100;
  border: solid #EEE 1px; 
  padding: 15px;
  margin-bottom: 20px;
  width: 100%; 
}

.input_control:focus {
  outline: none;
  border: solid #03be33 1px; 
}

button {
  display: block;
  background: #03be33;
  color: white;
  border-radius: 15px;
  width: 100%;
  font-size: 15px;
  font-weight: 700;
  padding: 15px;
  border: none;
  margin-top: 15px;
}

a, a:hover, a:visited {
  color: #2963b0;
}

.forget_password_container {
  padding: 20px;
}

#rememberMe {
  border-radius: 25%;
  margin-bottom: 20px;
}

#rememberMeLabel {
  font-weight: 100;
}
</style>
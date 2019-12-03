<template>
  <div class="container">
    <div class="logo">
      <img src="/images/logo.png" alt="">
    </div>

    <h5>Sign in</h5>
    <input class="input_control" type="text" id="name" placeholder="John Doe">
    <input class="input_control" type="password" id="password" placeholder="********">
    <label>
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
img {
  width: 100%;
}

.logo {
  padding: 10px 20px 80px;
}

.text-center {
  text-align: center;
}

h5 {
  font-weight: 300;
  margin-bottom: 20px;
}

.input_control {
  border-radius: 15px;
  border: solid #03be33 1px; 
  padding: 10px;
  margin-bottom: 20px;
  width: 100%; 
}

button {
  display: block;
  background: #03be33;
  color: white;
  border-radius: 15px;
  width: 100%;
  font-size: 15px;
  padding: 10px;
  border: none;
  margin-top: 15px;
}

a, a:hover, a:visited {
  color: #2963b0;
}

.forget_password_container {
  padding-top: 10px;
}

#rememberMe {
  border-radius: 25%;
}
</style>
<template>
  <div class="home">
    <div class="landing-page">
      <div class="container flex justify-between">
          <div class="max-h-56 mt-80 translate">
            <h1 class="text-7xl text-white">IT WORLD INDONESIA</h1>
            <p class="text-4xl text-white">We are a community that wants to build a free place<br>to study and here we learn together.</p>
          </div>
          <div class="card">
            <form action="" class="bundle">
              <input type="email" name="email" id="email" placeholder="example@domain.com" class="p-8 py-4">
              <input type="password" id="pwd" name="pwd" placeholder="password" class="p-8 py-4">
              <input type="submit" value="Login" class="blue py-2">
              <h1 class="text-white text-3xl">or</h1>
              <a href=""><div class="blue py-2 tex-white link">Register</div></a>
            </form>
            <div class="other-login">
            </div>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {
  }
}
</script>

<style scoped>

.landing-page {
  background-image: url('../assets/bg.jpg');
  background-attachment: fixed;
  background-repeat: no-repeat;
}

.container {
  background-color: rgba(0, 13, 24, 0.75);
  height: 100vh;
  max-width: 100vw;
}

.translate {
  -ms-transform: translateY(50%);
  transform: translateY(50%);
}

.card {
  height: 70vh;
  width: 35vw;
  -ms-transform: translateY(20%);
  transform: translateY(20%);
  margin-right: 5%;
  border-radius: 30px;
  border: 1px solid white;
  background-color: rgba(0, 0, 0, 0.37);
}

.card form {
  margin: 10% auto;
  max-width: 85%;
}

.bundle {
  display: flex;
  flex-direction: column;
}

.bundle input {
  margin-top: 5%;
  height: auto;
  border-radius: 30px;
  background-color: #333232;
  font-size: 25px;
}

.blue {
  background-color: #0085FF !important;
  color: #fff !important;
  font-size: 28px !important;
  font-weight: 600;
  border-radius: 30px;
}

form h1 {
  margin: 10px 0;
}

form h1,
form .link {
  text-align: center;
}


</style>

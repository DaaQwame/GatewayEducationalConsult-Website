<template>
<div class="pee">
<a :aria-expanded="isActive" :class="{ 'is-active': isActive }" role="button" class="navbar-burger" aria-label="menu" data-target="collapse" @click="isActive = !isActive" >
  <span></span>
  <span></span>
  <span></span>
</a>
<div class="yolo">
  <img class="mix" src="./assets/logo.jpeg">
  <h3 class="malt">YOUR GATEWAY TO INTERNATIONAL <br>ACADEMIC SUCCESS</h3>
</div>
</div>
<div class="hold">
<div id="collapse" :class="{ 'is-active': isActive }" class="navbar-menu is-paddingless">
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
    <router-link to="/service">Service</router-link>
    <router-link to="testimonial">Testimonial</router-link>
    <router-link to="contact">Contact Us</router-link>
  </nav>
</div>
</div>
 <router-view/>
</template>
<script>
export default {
  data () {
    return {
      isActive: false,
      showNavbar: true
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.malt{
  transform: translate(6%,-50px);
  font-weight: bolder;
  font-size: 18px;
  color:rgb(58, 58, 148) ;
  margin-bottom: -3%;
}
.mix{
  width: 16%;
  margin-right: 25%;
}
@media only screen and (max-width: 700px) {
  nav{
  background-color: rgb(58, 58, 148);
}
.yolo{
  background-color: #fff;
}
 .pee{
    background-color: orange;
  }
.malt{
  transform: translate(-1%,-8px);
  font-weight: bolder;
  font-size: 18px;
  margin-bottom: -1%;
}
.mix{
  width: 50%;
  margin-left: 80px;
}
}
nav {
  padding: 12px 40px;
  display: inline-block;
  padding-left: 18%;
}
.hold{
  background-color: rgb(58, 58, 148);
}
nav a {
  font-weight: bold;
  color: #fff;
  text-decoration: none;
  display: inline-block;
  padding: 20px 50px;
  text-transform: uppercase;
  padding-top: 5%;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

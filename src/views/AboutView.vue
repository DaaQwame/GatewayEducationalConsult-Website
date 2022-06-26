<template>
<header class="lad">
    <h1 class="load">ABOUT US</h1>
</header>

<!---------about us------>


       <section class="about-us">
            <div class="row">
                <div class="about-col">
                    <h1>WHAT WE DO</h1>
                    <h4 class="agent">Gateway Educational Consult purposely help students who are far and near
                        who want to continue their academic journey abroad to get that great
                        opportunity to study in their dream country.Gec has come to help alot
                        of students who never knew they would get to that destination, to get</h4>
                        <h5 class="some">into that position.Since this institution started operating,it's has
                         helped about thousands of students to get into their dream country to
                         study.Apply scholarship through gateway educational consult to enable
                         your vision of studying abroad come into reality.</h5>
                         <router-link to="history"><button class="nnn">READ MORE ABOUT GEC</button></router-link>
                </div>
                <div class="about-col">
                    <img src="../assets/abt.jpg">
                </div>
                </div>
       </section>

       <!-------our main office------>

       <div class="nunu">
    <div class="yu">
      <h1 class="bb">APPLY YOUR SCHOLARSHIP THROUGH GEC NOW </h1>
    </div>
  </div>
  <section class="mom">
        <h1 class="eat">OUR MAIN OFFICES</h1>
        <p>Countries we have our offices that you can locate us</p>
        <div class="raw">
          <div class="camp-col">
            <img class="pope" src="../assets/office1.jpg">
            <div class="layer">
              <h3>RUSSIA</h3>
            </div>
          </div>
        <div class="camp-col">
            <img class="pope" src="../assets/office2.jpg">
            <div class="layer">
              <h3>CHINA</h3>
            </div>
          </div>
        <div class="camp-col">
            <img class="pope" src="../assets/office3.webp">
            <div class="layer">
              <h3>AUSTRALIA
              </h3>
            </div>
          </div>
        </div>
  </section>

<!----------footer------>
<footer>
     <div class="container">
       <ul class="flex">
         <li><router-link class="you" to="/">Home</router-link></li>
         <li><router-link class="you" to="/About">About</router-link></li>
         <li><router-link class="you" to="/Service">Service</router-link></li>
         <li><router-link class="you" to="/Testimonial">Testimonial</router-link></li>
         <li><router-link class="you" to="/Contact">Contact</router-link></li>
       </ul>
       <ul class="flex">
         <router-link class="you" to="/"><li><i class="fab fa-facebook"></i></li></router-link>
        <router-link class="you" to="/"><li><i class="fab fa-twitter"></i></li></router-link>
        <router-link class="you" to="/"><li><i class="fab fa-instagram"></i></li></router-link>
       <router-link class="you" to="/"><li><i class="fab fa-youtube"></i></li></router-link>
       </ul>
         <p class="run"><i class="fa-regular fa-copyright"></i> 2022 Gateway Educational Consult</p>
     </div>
     </footer>
</template>
<script>

</script>

<style>
.nnn{
  background-color: transparent;
  margin-top: 15px;
  padding: 12px 20px;
  color: blue;
  border: 2px solid black;
}
.agent{
    color: brown;
}
.some{
    color: black;
}
.row{
    margin: 5%;
    display: flex;
    justify-content: space-between;
}
.about-us{
    width: 80%;
    margin: auto;
    padding-top: 80px;
    padding-bottom: 50px;
}


.about-col{
    flex-basis: 44%;
    padding: 30px 2px;
    margin-bottom: 5%;
}

.about-col img{
    width: 100%;
}

.about-col h1{
    padding-top: 0;
}

.about-col p{
    padding: 15px 0 25px;
}
.lad{
  min-height: 40vh;
  width: 100%;
  margin-top: -8px;
  background: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.6)), url("../assets/about.jpg");
  background-size: cover;
  background-position: center;
  position: rel6ative;
}
.nunu{
  min-height: 50vh;
  width: 100%;
  margin-top: -8px;
  margin-bottom: 0%;
  background-image: url("../assets/gec.jpg");
  background-size: cover;
  background-position: center;
  margin-top: 70px;
  position: relative
}
.yu{
  height: 50vh;
  background: rgba(0,0,0,0.7);
}
.bb{
  margin-top: -22px;
  color: #fff;
  padding-top: 140px;
  font-size: 22px;
}
.eat{
  font-size: 20px;
  padding-top: 100px;
}
.camp-col{
  flex-basis: 32%;
  border-radius: 10px;
  margin-bottom: 30px;
  position: relative;
  overflow: hidden;
}
.camp-col .pope{
  width: 100%;
}
.layer{
  color: #111;
}
.load{
  color: #fff;
  font-size: 30px;
  padding-top: 160px;
  font-weight: bolder;
}

@media only screen and (max-width: 700px) {
  .about-col, img{
    width: 100%;
}
}
</style>
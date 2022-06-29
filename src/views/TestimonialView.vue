<template>
 <div class="uss">
    <div class="ucc">
    <h1 class="ttc">TESTIMONIALS</h1>
    </div>
  </div>
<div class="testimonials">
    <div class="title">
      <h2>TESTIMONIALS</h2>
        <p class="gut">What our students says about us</p>
    </div>
    <div class="ram">
        <div class="code">
         <p class="papa"><i class="fas fa-quote-left quote"></i>Gateway Educational Consult has really helped me in my academic journey.This
            organization helped me through counselling me to get a school i want to
            study and also they helped me get acomodation and work as well,in fact
            they really did a marvelous job for me as a student and i really
            thank them for their support,and i want anyone who have passion
            of travelling abroad to study to approach gateway educational
            consult team to help his dream of studying abroad come into reality</p>
        <h4>John Smith</h4>
        </div>
        <div class="code">
        <p class="papa"><i class="fas fa-quote-left quote"></i>I gained admision to study in university of munich in germany by the help of
            gateway educational consult.I pursued computer science and now i'm working
            as a web developer on my own.This organization tried all their possible
            best to help me get into germany to study in a school of my choice
            i'm now doing big projects to renowned institutions,so gateway educational
            consult is the best way to help you succeed in travelling to other country
            to study </p>
        <h4>Patrict Walker</h4>
        </div>
        <div class="code">
        <p class="papa"><i class="fas fa-quote-left quote"></i>I'm very happy i had an early encounter with gateway educational consult
            to help me get scholarship to study abroad.GEC team really helped
            me to get everything i need to get to study at the country i want
            to study,they guided very well to acquire everything necessary
            to take me there.I recommend gateway educational consult for
            each and everyone who want to continue his or her education
            abrod</p>
        <h4>James Wilson</h4>
        </div>
    </div>
</div>
<div class="ram">
        <div class="code">
         <p class="papa"><i class="fas fa-quote-left quote"></i>I had a very encouraging, supportive and helpful experience with you and
         your organisation. Right from making
         application uptill visa approval, you and your organisation was very helpful and easily approachable.
         Even though I was applying for a very specialised branch of medicine, I didn't feel lost or not guided. This is the sole
         reason I have even recommended you to my friends and hope that you continue this commendable service of yours.
         </p>
        <h4>Beatrice Ankomah</h4>
        </div>
        <div class="code">
        <p class="papa"><i class="fas fa-quote-left quote"></i>I am glad to have had the opportunity to meet the full team of Gec!
         They are truly great, and do a
         great job in mentoring students to study abroad. They have informed me everything before hand, and made
         sure everything was done at the right time. My visa process would not have been so smooth if I didn't go to
         Gec. I am very happy with the quality of assistance given by them. I highly recommend Gec
          to students, who are planning to study abroad.
         </p>
        <h4>Linda Hamilton</h4>
        </div>
        <div class="code">
        <p class="papa"><i class="fas fa-quote-left quote"></i>I would like to take a moment appreciate your efforts in
         helping me in my dream of studying abroad. You and your team had done a great job all through the journey. Right
          from the offer till getting the visa done you have helped and guided me. I would also want thank you for the
           services. All the best. </p>
        <h4>Lucy Linneson</h4>
        </div>
    </div>
<div class="with">
    <div class="room">
      <h2 class="pen">Email us to get our best counselling to study abroad</h2>
      <p>gatewayeducationalconsult@gmail.com</p>
    </div>
  </div>
<!----------footer------->
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
.gut{
  font-size: 15px;
}
.papa{
  color: #fff;
}
.title h2{
  color: #111;
  font-size: 25px;
  padding-top: 100px;
}
.ram{
  margin-top: 5%;
  display: flex;
  justify-content: space-between;
}
i.quote{
  color: orange;
  font-size: 25px;
}
.code h4{
  color: orange;
}
.code{
  flex-basis: 31%;
  background: black;
  border-radius: 10px;
  margin-bottom: 5%;
  padding: 20px 12px;
  box-sizing: border-box;
}

.ucc{
  min-height: 40vh;
  width: 100%;
  margin-top: -8px;
  background: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.6)), url("../assets/testimony.jpg");
  background-size: cover;
  background-position: center;
  position: rel6ative;
}
.ttc{
  color: #fff;
  font-size: 30px;
  padding-top: 160px;
  font-weight: bolder;
}
.pen{
  margin-top: -22px;
  color: #fff;
  padding-top: 95px;
}

.room p{
  color: orange;
  font-size: 20px;
}
.room{
  height: 50vh;
  background: rgba(0,0,0,0.7);
  padding-top: 5%;
}
.with{
  min-height: 50vh;
  width: 100%;
  margin-top: -8px;
  margin-bottom: 0%;
  background-image: url("../assets/tt.jpg");
  background-size: cover;
  background-position: center;
  margin-top: 70px;
  position: relative
}
@media only screen and (max-width: 700px) {
  .room{
    padding-top: 16%;
  }
  .ram{
    flex-direction: column;
  }
}
 </style>

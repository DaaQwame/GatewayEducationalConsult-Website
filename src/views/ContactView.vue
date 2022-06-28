<template>
      <div class="slip">
    <div class="lup">
    <h1 class="last">CONTACT US</h1>
    </div>
  </div>
  <div class="myth">
    <h2>Moscow,Russia</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m23!1m12!1m3!1d71844.9664525233!2d37.54726049598515!3d55.7558060865949!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m8!3e6!4m0!4m5!1s0x46b54afc73d4b0c9%3A0x3d44d6cc5757cf4c!2sMoscow%2C%20Russia!3m2!1d55.755826!2d37.6172999!5e0!3m2!1sen!2sgh!4v1652263802597!5m2!1sen!2sgh"
     width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
     <p>Gateway Education Consult has it main branch in Russia in it's capital city called Moscow,we are located along arbat street</p>
      <p>Where a new hotel is built called Izmailovo hotel,and this hotel is the biggest hotel ever built in moscow of which anyone</p>
      <p>Can find GEC opposite Izmailovo hotel.OR you can call us our office line on,Main:+79771513735 | +233245766604.</p>
      <p>So we can meet you when you get closer to hotel,it's has been long since we moved to that place and anyone within</p>
      <p>Can even direct you to our main office.</p>
  </div>
   <section class="contact-us">
        <div class="mode">
            <div class="contact-col">
                <div>
                    <i class="fas fa-home"></i>
                    <span>
                        <h5>Moscow</h5>
                        <p>Arbat Street,Near Izmailovo Hotel</p>
                    </span>
                </div>
                <div>
                    <i class="fas fa-phone"></i>
                    <span>
                        <h5>+797-71513735 | +233-245766604</h5>
                        <p>Monday to Friday, 8AM to 6PM</p>
                    </span>
                </div>
                <div>
                    <i class="fas fa-envelope-square"></i>
                    <span>
                        <h5>gatewayeducational<br>consult@
                            gmail.com</h5>
                        <p>Email us your query</p>
                    </span>
                </div>
            </div>
            <div class="contact-col">
                <form action="post">
                    <input type="text" id="name" placeholder="Enter your full name" required>
                    <input type="email" id="email" placeholder="Enter your email address" required>
                    <input type="text" id="subject" placeholder="Enter your subject" required>
                    <textarea rows="8" id="message" placeholder="Type your message here" required></textarea>
                    <button type="submit" id="submit" class="hero">Send</button>
                </form>
            </div>
        </div>
   </section>
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
.contact-us{
    width: 70%;
    padding-top: 100px;
    margin: auto;
}
iframe{
    width: 50%;
}
.contact-col{
    flex-basis: 48%;
    margin-bottom: 30px;
}
.contact-col div{
    display: flex;
    align-items: center;
    margin-bottom: 40px;
}
.contact-col div .fas{
    font-size: 28px;
    color: orange;
    margin: 10px;
    margin-right: 30px;
}
.contact-col div p{
    padding: 0;
}
.contact-col div h5{
    font-size: 20px;
    margin-bottom: 5px;
    color: #555;
    font-weight: 400;
}
.contact-col input, .contact-col textarea{
    width: 100%;
    padding: 15px;
    margin-bottom: 17px;
    outline: none;
    border: 1px solid #ccc;
}
.hero{
    margin-bottom: 30px;
    padding: 12px 25px;
    background: transparent;
    color: orange;
    border: 1px solid #ccc;
}
.mode{
    margin-bottom: 5%;
    display: flex;
    justify-content: space-between;
}
.myth h2{
    color: #111;
}
@media (max-width: 700px) {
  .rot{
    margin-top: -13%;
  }
  .dot{
    padding-left: 15%;
  }
.hero{
    width: 30%;
    margin-right: 8%;
    padding-right: 15%;
    margin-bottom: 0px;
}
  .mode{
      flex-direction: column;
  }
 .myth iframe{
     width: 100%;
     height: 100%;
  }
}
.myth iframe{
  width: 80%;
}
.myth h2{
  padding-top: 80px;
}
.lup{
  min-height: 40vh;
  width: 100%;
  margin-top: -8px;
  background: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.6)), url("../assets/tt2.jpg");
  background-size: cover;
  background-position: center;
  position: rel6ative;
}
.last{
  color: #fff;
  font-size: 30px;
  padding-top: 160px;
  font-weight: bolder;
}
.rot{
  color: #fff;
  padding-top: 7%;
  font-size: 25px;
}
.dot{
  background: #111;
  height: 40vh;
  background: rgba(0,0,0,0.6);
}


</style>
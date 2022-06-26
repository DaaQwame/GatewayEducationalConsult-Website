<template>
  <header class="make">
    <h1 class="mass">OUR SERVICE</h1>
</header>

<!-----service------>
<div class="service">
    <div class="dip">
      <img src="../assets/service2.jpg">
    </div>
    <div class="slot">
      <h2 class="rat">WHAT WE OFFER FOR OUR STUDENTS</h2>
      <p>Gateway Educational Consult provides quality service to their clients regarding career counseling, selecting</p>
      <p>international universities and programmes, admission application process, scholarship</p>
      <p>guidance for their meritorious students, visa application support, accommodation support in</p>
     <p> abroad, pre departure support, after arrival support etc. We serve the best quality</p>
     <p> counselling to our valuable students through experts and skilled consultants regarding that
       fields.</p>
    </div>
    <div class="mini">
      <div class="abb">
        <h3>Career counseling</h3>
        <p>We can guide you based on your previous studies, academic,
           results career perspectives, financial support, future plan and so on.
        </p>
        <h3>University and programme selection</h3>
        <p>Choosing from so many universities and programmes, deciding
          what to study and where could be difficult task for the students.
         Therefore, we will assist you to choose best university and,
         programme after finalizing the universities our counselors will
         give a broad overview on that universities and the selected programmes.
        </p>
      </div>
         <div class="abb">
        <h3>Admission application support</h3>
        <p>After choosing the Universities and desired subjects, our experts
          will guide you regarding how to write your SOP (Statement of
         purpose) letter, Curriculum of Vitae and so on. Later, our experts
         will apply to those universities on your behalf.
        </p>
        <h3>Scholarship guidance</h3>
        <p>
          Providing Scholarships to the meritorious students is one of the
          main mottos of GEC. Our consultants find out various scholarships
         offered by the universities for the international students, then
         help our students to write the motivation letter and guide them
         to make themselves competitive and eligible to grab that
         scholarship.We also recommend our special talented students to the universities we work with.
        </p>
      </div>
         <div class="abb">
        <h3>Visa application assistance</h3>
        <p>Our skilled counsellors assist for the visa application process
          including translating the documents and sending the important
         document through courier if needed.
        </p>
        <h3>Accommodation assistance</h3>
          <p> GEC helps their students to apply or find the student dormitory or
              student apartments. Sometimes area based accommodation
              request and sharing accommodation priorities are also
              considered.Our counsellors make reasonable conversation with
              the students and find out the best possible accommodation
              service for the students according to their demands regarding
              their budget, comfort and other convenient things.
          </p>
      </div>
    </div>
  </div>
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
.abb{
  flex-basis: 31%;
  background: black;
  border-radius: 10px;
  margin-bottom: 5%;
  padding: 20px 12px;
  box-sizing: border-box;
}
.dip img{
  width: 50%;
  padding-top: 50px;
}
.abb h3{
  color: orange;
}
.abb p{
  color: #fff;
}
.mini{
  margin-top: 5%;
  display: flex;
  justify-content: space-between;
}
.mass{
  color: #fff;
  font-size: 30px;
  padding-top: 160px;
  font-weight: bolder;
}
.rat{
  padding-top: 100px;
}
.make{
  min-height: 40vh;
  width: 100%;
  margin-top: -8px;
  background: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.6)), url("../assets/service1.png");
  background-size: cover;
  background-position: center;
  position: rel6ative;
}

@media only screen and (max-width: 700px) {
  .mini{
  flex-direction: column;
}
.dip img{
  width: 100%;
}
}
</style>

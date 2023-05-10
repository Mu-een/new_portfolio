<template>
  <NavBar/>

  <!-- ============================landing page ===================================================-->
  <div class="home container-fluid">
    <div class="h1-container-fluid">
      <h1 class="display-1 text-center text-light">I'm <strong>Mu-een Slamat</strong></h1>
      <h2 class="text-center text-light" style="font-size: 40px">A Web Developer</h2>
      <button class="mx-auto d-flex">Download CV <i class="bi bi-download"></i></button>
    </div>
  </div>

  <!-- ================================about me =================================================-->
  <section>
    <div class="about" style="height: 100vh; width: 100vw;">
      <h2 class="display-2 text-center text-light">About Me</h2>
      <div class="aboutMe">
        <div class="me">
          <img src="https://i.postimg.cc/hGcYjNNN/DSC-3547-1-removebg-preview.png" alt="me" style="max-width: 100%; height: auto;">
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt suscipit consectetur repudiandae deserunt illo,
           ducimus quas eius veniam quaerat vel voluptatem dicta minus nam fugiat aspernatur dolorem fuga culpa debitis?
        </p>
      </div>
    </div>
  </section> 

  <!-- ============================ resume =============================== -->
  <section id="resume">
    <div class="resume " style="height: 100vh;width:100vw">
      <h2 class="display-2 text-center resumeTitle text-light">Resume</h2>
     
     <div class=" myResume d-flex">

       <div class="row">
         <div class="card bg-light text-dark" style="width: 18rem;border-radius: 23px;">
       <img src="https://i.postimg.cc/xCsTHnfC/download.png" class="card-img-top mt-3" alt="" style="border-radius: 10px;">
       <div class="card-body">
         <h5 class="card-title text-center">Web Development Intern at LC Studio</h5>
         <p class="card-text text-center ">April 2023 - Present</p>
       </div>
     </div>
   </div>
   
   <div class="row">
     <div class="card bg-light text-dark" style="width: 18rem;border-radius: 23px;">
   <img src="https://i.postimg.cc/7hnv7NMN/1565593241244.jpg" class="card-img-top mt-3" alt="" style="border-radius: 10px;">
   <div class="card-body">
     <h5 class="card-title text-center">Studied Web Development at Life Choices Coding Academy</h5>
     <p class="card-text text-center ">October 2022 - March 2023</p>
   </div>
   </div>
   </div>
   
   <div class="row">
     <div class="card bg-light text-dark" style="width: 18rem;border-radius: 23px;">
   <img src="https://i.postimg.cc/j2Px1N6W/cisco-networking-academy-logo-1.png" class="card-img-top mt-3" alt="" style="border-radius: 10px;">
   <div class="card-body">
     <h5 class="card-title text-center">Studied CCNA and I.T Essentials</h5>
     <p class="card-text text-center ">2021</p>
   </div>
   </div>
   </div>
   
   <div class="row">
     <div class="card bg-light text-dark" style="width: 18rem;border-radius: 23px;">
   <img src="https://i.postimg.cc/fTgbYF3T/download.png" class="card-img-top mt-3" alt="" style="border-radius: 10px;;">
   <div class="card-body">
     <h5 class="card-title text-center">Worked at Open Box as a Junior I.T Technician</h5>
     <p class="card-text text-center ">November 2019 - January 2020</p>
   </div>
   </div>
   </div>
     </div>
    </div>

  </section>

  <!-- =================projects ============================================-->
  <section>
    <div class="projects">
      <h2 class="display-2 text-center projectsTitle text-light">Projects</h2>
      <div class="card bg-dark text-white">
        <img src="https://i.postimg.cc/bwSmLJh5/recha-oktaviani-h2a-DKwig-Qe-A-unsplash.jpg" class="card-img calculatorPic" alt="">
        <div class="card-img-overlay">
          <h5 class="card-title text-dark">JavaScript Calculator</h5>
          <a href="https://mueen-calculator.netlify.app/" target="_blank"><button>View site</button></a>
        </div>
      </div>

      <div class="card bg-dark text-white">
        <img src="https://i.postimg.cc/T3XLjcvL/joel-muniz-l-UK16p-Jt-CM-unsplash.jpg" class="card-img calculatorPic" alt="">
        <div class="card-img-overlay">
          <h5 class="card-title text-light">CAPSTONE: Celebrity Boxing Events E-commerce</h5>
          <a href="https://mueenslamat-capstone-project.web.app/" target="_blank"><button>View site</button></a>
        </div>
      </div>

    </div>

  </section>

  <!-- ===================testimonials =======================================-->
  <section>
    <div class="testimonials">
      <h2 class="display-2 text-center testimonialsTitle text-light">Testimonials</h2>
    </div>
  </section>

  <!-- contact -->
  <div class="contactMe">
    <div class="text-center contact">
      <h2 class="display-2 text-light">Let's talk</h2>
      <p style="font-size: 30px;" class="text-light">Any questions or remarks? Just write me a message! <i class="bi bi-emoji-smile"></i></p>
    </div>
    <form action="https://formspree.io/f/xbjeqabp"  method="POST" >
      <div class="mb-3 w-25 mx-auto" style="font-size: 18px;">
        <label for="exampleFormControlInput1" class="form-label" style="line-height: 2.5rem;">Name</label>
        <input type="text" class="form-control" id="exampleFormControlInput1" name="name" required>
        <label for="exampleFormControlInput1" class="form-label" style="line-height: 2.5rem;">Last Name</label>
        <input type="text" class="form-control" id="exampleFormControlInput1" name="lastName" required>
        <label for="exampleFormControlInput1" class="form-label" style="line-height: 2.5rem;">Subject</label>
        <input type="text" class="form-control" id="exampleFormControlInput1" name="subject" required>
        <label for="exampleFormControlInput1" class="form-label" style="line-height: 2.5rem;">Contact Details</label>
        <input type="text" class="form-control" id="exampleFormControlInput1" name="contactDetails" required>
      </div>
      <div class="mb-3 w-25 mx-auto"  style="font-size: 18px;">
        <label for="exampleFormControlTextarea1" class="form-label">Message</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" name="message" required></textarea>
      </div>
      <button type="submit" class="form-control w-25 mx-auto">Send Message <i class="bi bi-box-arrow-in-right"></i></button>
    </form>
    <ul class="socials text-center mx-auto d-flex">
      <a href="https://www.linkedin.com/in/mueenslamat/" target="_blank" style="color: white;"><i class="bi bi-linkedin"></i></a>
      <a href="https://github.com/Mu-een" target="_blank" style="color: white;"><i class="bi bi-github"></i></a>
    </ul>
  </div>
  <FooterC/>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import FooterC from '@/components/FooterC.vue';

export default {
  name: 'HomeView',
  components: {
    NavBar,
    FooterC
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Prompt:wght@700&display=swap');

/* =========================== landing page css ===================================================*/
.home {
  background-color: #1C2826;
  width: 100vw;
  min-height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
}

h1 strong {
  color: #FBCA1F;
}
.h1-container-fluid{
  position: absolute;
  top: 50%;
  left: 50%;  
  transform: translate(-50%, -50%);
  font-family: 'Jost', sans-serif;
  color: #2c3333;
  
}

button {
  background: #FBCA1F;
  font-family: inherit;
  padding: 0.6em 1.3em;
  font-weight: 900;
  font-size: 18px;
  border: 3px solid black;
  border-radius: 0.4em;
  box-shadow: 0.1em 0.1em;
  margin-top: 100px;
}

button:hover {
  transform: translate(-0.05em, -0.05em);
  box-shadow: 0.15em 0.15em;
}

button:active {
  transform: translate(0.05em, 0.05em);
  box-shadow: 0.05em 0.05em;
}

/* =========================== about me section css ======================================*/
.about {
  background-color: #1C2826;
  font-family: 'Prompt', sans-serif;
}

.aboutMe {
  font-family: 'Outfit', sans-serif;
  display: flex;
  flex-direction: row;
  align-items: center;
  background-color: #FBCA1F;
  margin: 100px;
  padding: 100px;
  border: 2px solid black;
  position:relative;
}

.aboutMe p {
  font-size: 1.2rem;
  line-height: 1.5;
  margin: 0;
}

.me {
  margin: 10px;
  position: relative;
  clip-path: circle(50% at 50% 50%);
}
.me:hover{ 
  transform: scale(1.10);
}

/* ===================== resume section css ================================ */
.resume {
  background-color: #1C2826;
  min-height: 100vh;
}

.resumeTitle {
  font-family: 'Prompt', sans-serif;
}
.myResume {
  padding-top: 60px;
  gap: 100px;
  margin: auto;
  justify-content: center;
}
.card {
  width: 190px;
  height: auto;
  color: white;
  background: rgb(46, 44, 44);
  transition: all 300ms;
}

.card-body {
  font-family: 'Outfit', sans-serif;
}
.card:hover {
  transform: scale(1.10);
}

  /* =====================projects section css ================================ */
.projects {
    background-color: #1C2826;
    min-height: 100vh;
  }

  .projectsTitle {
    font-family: 'Prompt', sans-serif;
  }

 .calculatorPic{
  height: 300px;
  width: 300px;
 }

   /* =====================testimonials section css ================================ */
.testimonials {
    background-color: #1C2826;
    min-height: 100vh;
  }

  .testimonialsTitle {
    font-family: 'Prompt', sans-serif;
  }

  /* =============== contact section css ========================*/
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');

.contactMe {
  background-color: #1C2826;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 130vh;
}

.contact {
  font-family: 'Prompt', sans-serif;
  padding-top: 20px;
}

form {
  font-family: 'Outfit', sans-serif;
  color: #FBCA1F;
}

button {
  background: #FBCA1F;
  font-family: inherit;
  padding: 0.6em 1.3em;
  font-weight: 900;
  font-size: 18px;
  border: 3px solid black;
  border-radius: 0.4em;
  box-shadow: 0.1em 0.1em;
}

button:hover {
  transform: translate(-0.05em, -0.05em);
  box-shadow: 0.15em 0.15em;
}

button:active {
  transform: translate(0.05em, 0.05em);
  box-shadow: 0.05em 0.05em;
}

.socials {
  gap: 20px;
  display: flex;
  padding: 20px;
  font-size: 30px;
  list-style-type: none;
  justify-content: center;
}

ul a:hover {
  transform: scale(1.10);
}

</style>

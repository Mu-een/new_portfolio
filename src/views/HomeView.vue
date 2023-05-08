<template>
  <NavBar/>

  <!-- ============================landing page ===================================================-->
  <div class="home container-fluid">
    <div class="h1-container-fluid">
      <h1 class="display-1 text-center">I'm Mu-een Slamat</h1>
      <h2 class="text-center" style="font-size: 40px">A Web Developer</h2>
      <button class="mx-auto d-flex">Download CV <i class="bi bi-download"></i></button>
    </div>
  </div>

  <!-- ================================about me =================================================-->
  <section>
    <div class="about" style="height: 100vh; width: 100vw;">
      <h2 class="display-2 text-center">About Me</h2>
      <div class="aboutMe">
        <ul class="my-stats text-center mx-auto">
          <li><i class="bi bi-calendar3"></i> 03/06/1999</li>
          <li><i class="bi bi-geo"></i> Athlone, Cape Town </li>
          <li><i class="bi bi-telephone"></i> 083 495 5213</li>
          <li><i class="bi bi-envelope"></i> mueenslam@gmail.com</li>
          <li><i class="bi bi-translate"></i> English and Afrikaans speaking</li>
        </ul>
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
    <div class="resume">
      <h2 class="display-2 text-center resumeTitle">Resume</h2>
    </div>
  </section>

  <!-- =================projects ============================================-->
  <section>
    <div class="projects">
      <h2 class="display-2 text-center projectsTitle">Projects</h2>
    </div>
  </section>

  <!-- ===================testimonials =======================================-->
  <section>
    <div class="testimonials">
      <h2 class="display-2 text-center testimonialsTitle">Testimonials</h2>
    </div>
  </section>

  <!-- contact -->
  <div class="contactMe">
    <div class="text-center contact">
      <h2 class="display-2">Let's talk</h2>
      <p style="font-size: 30px;">Any questions or remarks? Just write me a message! <i class="bi bi-emoji-smile"></i></p>
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
      <a href="https://www.linkedin.com/in/mueenslamat/" target="_blank" style="color: black;"><i class="bi bi-linkedin"></i></a>
      <a href="https://github.com/Mu-een" target="_blank" style="color: black;"><i class="bi bi-github"></i></a>
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

/* =========================== landing page css ===================================================*/
.home {
  background: linear-gradient(rgba(101, 100, 100, 0), #ECF2FF), url(https://i.postimg.cc/1tQtnDk7/aaron-burden-Bycd2w-F5v-QU-unsplash.jpg);
  width: 100vw;
  min-height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
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
  background-color: #ECF2FF;
  font-family: 'Tajawal', sans-serif;
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
.my-stats {
  list-style-type: none;
  margin: 0;
  padding: 30px;
  margin-left: 50px;
  /* display: flex; */
  font-family: 'Outfit', sans-serif;
}

.my-stats:hover {
  transform: scale(1.10);
}

/* ===================== resume section css ================================ */
.resume {
  background: url(https://i.postimg.cc/V6jftJPt/joao-ferrao-4-Yzrc-DNc-RVg-unsplash.jpg) ;
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
  }

  .resumeTitle {
  font-family: 'Tajawal', sans-serif;
  }

  /* =====================projects section css ================================ */
.projects {
  background: url(https://i.postimg.cc/FF8Xh8sw/sigmund-4-UGmm3-WRUo-Q-unsplash.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
  }

  .projectsTitle {
  font-family: 'Tajawal', sans-serif;
  }

   /* =====================testimonials section css ================================ */
.testimonials {
  background: url(https://i.postimg.cc/G2FpnRvP/javier-allegue-barros-i5-Kx0-P8-A0d4-unsplash.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
  }

  .testimonialsTitle {
  font-family: 'Tajawal', sans-serif;
  }

  /* ===============contact section css ========================*/
  @import url('https://fonts.googleapis.com/css2?family=Jost:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');

.contactMe {
  background:  linear-gradient(rgba(101, 100, 100, 0), #ecf2ff), url(https://i.postimg.cc/0yWkCLj2/elcarito-MHNj-EBe-LTgw-unsplash.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 115vh;
}

.contact {
  font-family: 'Jost', sans-serif;
  padding-top: 20px;
}

form {
  font-family: 'Outfit', sans-serif;
  color: black;
  text-shadow: 2px 2px 2px white;
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

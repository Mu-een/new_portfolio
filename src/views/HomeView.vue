<template>
  <NavBar/>
  <div class="home container-fluid">
    <div class="h1-container-fluid">
      <h1 class="display-1 text-center">Hi! I'm Mu-een Slamat</h1>
      <h2 class="text-center" style="font-size: 40px">Web Developer</h2>
      <button class="mx-auto d-flex">Download CV</button>
    </div>
  </div>

  <section>
    <div class="about" style="height: 100vh; width: 100vw;">
      <h2 class="display-2 text-center">About Me</h2>
      <div class="aboutMe">
        <div class="me">
          <img src="https://i.postimg.cc/hGcYjNNN/DSC-3547-1-removebg-preview.png" alt="me" style="max-width: 100%; height: auto;">
        </div>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
          Praesentium placeat nulla obcaecati, culpa nihil modi? Accusantium velit error praesentium optio nisi, impedit 
          perspiciatis repudiandae, dignissimos eligendi laborum iste modi ducimus!</p>
        </div>
    </div>
  </section> 
</template>

<script>
import NavBar from '@/components/NavBar.vue';

export default {
  name: 'HomeView',
  components: {
    NavBar
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');

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

.about {
  background-color: #ECF2FF;
  font-family: 'Tajawal', sans-serif;
}

.aboutMe {
  font-family: 'Outfit', sans-serif;
  display: block;
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
  position: absolute;
}
</style>

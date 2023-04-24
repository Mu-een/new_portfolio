<template>
  <NavBar/>
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
      name: 'ContactView',
      components : {
        NavBar,
        FooterC
      }
    }
  </script>
  
  <style scoped>
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');

.contactMe {
  background:  linear-gradient(rgba(101, 100, 100, 0), #ecf2ff), url(https://i.postimg.cc/0yWkCLj2/elcarito-MHNj-EBe-LTgw-unsplash.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 110vh;
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
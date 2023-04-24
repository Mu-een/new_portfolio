<template>
  <NavBar/>
    <div class="testimonials">
    </div>
    <FooterC/>
  </template>
  
  <script>
  import NavBar from '@/components/NavBar.vue';
  import FooterC from '@/components/FooterC.vue';
    export default {
      name: 'TestimonialsView',
      components : {
        NavBar,
        FooterC
      }
    }
  </script>
  
  <style scoped>
  .testimonials {
    background: url(https://i.postimg.cc/G2FpnRvP/javier-allegue-barros-i5-Kx0-P8-A0d4-unsplash.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
    filter: blur(5px);
  }
  </style>
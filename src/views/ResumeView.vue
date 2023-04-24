<template>
  <NavBar/>
    <div class="resume">
    </div>
    <FooterC/>
  </template>
  
  <script>
  import NavBar from '@/components/NavBar.vue';
  import FooterC from '@/components/FooterC.vue';
    export default {
      name: 'ResumeView',
      components : {
        NavBar,
        FooterC
      }
    }
  </script>
  
  <style scoped>
  .resume {
    background: url(https://i.postimg.cc/V6jftJPt/joao-ferrao-4-Yzrc-DNc-RVg-unsplash.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
    filter: blur(5px);
  }

  </style>
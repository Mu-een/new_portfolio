<template>
  <NavBar/>
    <div class="projects">
    </div>
    <FooterC/>
  </template>
  
  <script>
  import NavBar from '@/components/NavBar.vue';
  import FooterC from '@/components/FooterC.vue';
    export default {
      name: 'ProjectsView',
      components : {
        NavBar,
        FooterC
      }
    }
  </script>
  
  <style scoped>
  .projects {
    background: url(https://i.postimg.cc/FF8Xh8sw/sigmund-4-UGmm3-WRUo-Q-unsplash.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
    filter: blur(5px);
  }

  </style>
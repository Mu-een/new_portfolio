<template>
  <nav class="navbar navbar-expand-lg container-fluid" style="width: 100vw;">
    <div class="container-fluid">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarTogglerDemo01"
        aria-controls="navbarTogglerDemo01"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0 mx-auto">
          <li class="nav-item">
            <router-link to="/" class="text-dark">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="text-dark">About Me</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/resume" class="text-dark">Resume</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/projects" class="text-dark">Projects</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/testimonials" class="text-dark">Testimonials</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="text-dark">Contact Me</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Urbanist:wght@700&display=swap');

nav {
  font-family: 'Urbanist', sans-serif;
  padding: 30px;
  background-color: #ECF2FF;
}
ul {
  display: flex;
} 
li {
  padding: 7px;
  list-style-type: none;
}
a {
  text-decoration: none;
  color: #435058;
  font-size: 25px;
  padding: 5px;
}
</style>

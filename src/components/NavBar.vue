<template>
  <nav class="navbar navbar-expand-lg container-fluid sticky-navbar" style="width: 100vw;">
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
            <router-link to="/" class="text-dark">Home <i class="bi bi-house"></i></router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="text-dark">About Me <i class="bi bi-info-circle"></i></router-link>
          </li>
          <li class="nav-item">
            <router-link to="#resume" class="text-dark">Resume <i class="bi bi-file-earmark-person"></i></router-link>
          </li>
          <li class="nav-item">
            <router-link to="#projects" class="text-dark">Projects <i class="bi bi-card-checklist"></i></router-link>
          </li>
          <li class="nav-item">
            <router-link to="#testimonials" class="text-dark">Testimonials <i class="bi bi-people"></i></router-link>
          </li>
          <li class="nav-item">
            <router-link to="#contact" class="text-dark">Contact <i class="bi bi-chat-left-dots"></i></router-link>
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

@import url('https://fonts.googleapis.com/css2?family=Ysabeau:wght@700&display=swap');


nav {
  font-family: 'Ysabeau', sans-serif;
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
li:hover {
  transform: scale(1.10);
  background-color: #FBCA1F;
  border-radius: 20px;
}
a {
  text-decoration: none;
  color: #435058;
  font-size: 25px;
  padding: 5px;
}
.sticky-navbar {
  position: sticky;
  top: 0;
  z-index: 1000;
}
</style>

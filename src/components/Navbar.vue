<template>
     <VueScrollFixedNavbar>
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
        <div class="container-fluid">
          <div class="navbar-brand"><router-link to="/" class="brand">Flight Ticekt<span>Booking</span></router-link></div>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon "></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <router-link class="nav-link" to="Reg">Register</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="Cancel">Login</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="About">About</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="Contact">Contact</router-link>
              </li>
              </ul>
            </div>
        </div>
      </nav>
    
    </VueScrollFixedNavbar>
</template>

<script>
export default {
       name:'navbar', 
    }
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  text-decoration: none;
}
html {
  scroll-behavior: smooth;
}
nav {
  width: 100%;
  position: sticky;
  background: rgba(0, 0, 0, 0.932);
  left: 0;
  right: 0;
  box-shadow: 0px 5px 8px rgba(0, 0, 0, 0.5);
  z-index: 10;
}
.navbar-brand .brand  {
  font-size: 30px;
  font-weight: 500;
  text-decoration: none;
  color: white;
}
.navbar-brand span {
  color: orange;
  transition: all 0.3s ease;
}
.nav-link {
  color: white !important;
  font-size: 21px;
  margin-left: 30px;
  font-family: sans-serif;
  transition: all 0.3s ease;
}
.nav-link:hover {
  color: orange !important;
}
@media (min-width: 300px) and (max-width: 460px) {
  .navbar-brand a{
    font-size: 20px !important;
  }
}
</style>
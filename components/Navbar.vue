<template>
<link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
    <nav class="navbar navbar-expand-lg">
      <a class="navbar-brand"><img src="/assets/logo_d.png" alt="logo_d" width="35"></a>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav ">
          <li class="nav-item mx-2 mt-2">
            <nuxt-link
            to="/"
            class="nav-link text-info"
            >Home
            </nuxt-link>
          </li>
          <li class="nav-item mx-2 mt-2">
            <nuxt-link
            to="/about"
            class="nav-link text-info"
            >About
            </nuxt-link>
          </li> 
          <li class="nav-item mx-2 mt-2">
            <nuxt-link
            to="/project"
            class="nav-link text-info"
            >Project
            </nuxt-link>
          </li>
          <li class="nav-item mx-2 mt-2">
            <nuxt-link
            to="/contact"
            class="nav-link text-info"
            >Contact
            </nuxt-link>
          </li>
        </ul>
      </div>
    </nav>
  </template>
    
<script>
  
</script>
  
<style scoped>
.navbar {
  background: #344a57;
  border: none;
  background: linear-gradient(50deg, #393b50, #2575fc);

  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

</style>
  
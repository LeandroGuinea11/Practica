<template>
  <nav class="navbar">
    <div class="navbar-container">
      <div class="logo">Practica</div>
      <ul class="nav-links">
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Servicios</a></li>
        <li><a href="#">Nosotros</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
    </div>
  </nav>
</template>

<script setup>

</script>

<style scoped>

.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #1e3a8a; 
  color: white;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
  z-index: 1000; 
}


.navbar-container {
  max-width: 1200px;
  margin: auto;
  padding: 0 20px;
  display: flex;
  height: 60px;
  align-items: center;
  justify-content: space-between;
}


.logo {
  font-size: 1.5rem;
  font-weight: bold;
}


.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links li a {
  text-decoration: none;
  color: white;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-links li a:hover {
  color: #cbd5e1; 
}


body {
  margin: 0;
  padding-top: 60px; 
}
</style>
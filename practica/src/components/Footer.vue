<template>
  <footer class="footer">
    <div class="footer-container">
      
      <!-- Sección principal del footer -->
      <div class="footer-content">
        
        <!-- Logo y descripción -->
        <div class="footer-section">
          <h3 class="footer-logo">¡Hala Madrid!</h3>
          <p class="footer-description">
            El club más grande del mundo. Forjando leyendas desde 1902 
            con 14 Ligas de Campeones y un palmarés inigualable.
          </p>
        </div>
        
        <!-- Enlaces rápidos -->
        <div class="footer-section">
          <h4>Enlaces Rápidos</h4>
          <ul class="footer-links">
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Historia</a></li>
            <li><a href="#">Plantilla</a></li>
            <li><a href="#">Noticias</a></li>
          </ul>
        </div>
        
        <!-- Información -->
        <div class="footer-section">
          <h4>Información</h4>
          <ul class="footer-links">
            <li><a href="#">Estadio Santiago Bernabéu</a></li>
            <li><a href="#">Contacto</a></li>
            <li><a href="#">Tienda Oficial</a></li>
            <li><a href="#">Real Madrid TV</a></li>
          </ul>
        </div>
        
        <!-- Redes sociales -->
        <div class="footer-section">
          <h4>Síguenos</h4>
          <div class="social-links">
            <a href="#" class="social-link">Facebook</a>
            <a href="#" class="social-link">Twitter</a>
            <a href="#" class="social-link">Instagram</a>
            <a href="#" class="social-link">YouTube</a>
          </div>
        </div>
        
      </div>
      
      <!-- Línea divisoria -->
      <hr class="footer-divider">
      
      <!-- Copyright -->
      <div class="footer-bottom">
        <p>&copy; 2024 Real Madrid Club de Fútbol. Todos los derechos reservados.</p>
        <p class="footer-slogan">Más que un club, una pasión eterna</p>
      </div>
      
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped>
.footer {
  background-color: #1e3a8a;
  color: white;
  margin-top: 40px;
}

.footer-container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 40px 20px 20px;
}

.footer-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
  margin-bottom: 30px;
}

.footer-section h3,
.footer-section h4 {
  color: white;
  margin-bottom: 15px;
  font-weight: bold;
}

.footer-logo {
  font-size: 1.5rem;
  color: #cbd5e1;
  margin-bottom: 10px;
}

.footer-description {
  line-height: 1.6;
  color: #cbd5e1;
  font-size: 0.9rem;
}

.footer-links {
  list-style: none;
  padding: 0;
  margin: 0;
}

.footer-links li {
  margin-bottom: 8px;
}

.footer-links a {
  color: #cbd5e1;
  text-decoration: none;
  font-size: 0.9rem;
  transition: color 0.3s ease;
}

.footer-links a:hover {
  color: white;
}

.social-links {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.social-link {
  color: #cbd5e1;
  text-decoration: none;
  font-size: 0.9rem;
  transition: color 0.3s ease;
}

.social-link:hover {
  color: white;
}

.footer-divider {
  border: none;
  height: 1px;
  background-color: #374151;
  margin: 30px 0 20px;
}

.footer-bottom {
  text-align: center;
  color: #9ca3af;
  font-size: 0.8rem;
}

.footer-bottom p {
  margin: 5px 0;
}

.footer-slogan {
  font-style: italic;
  color: #cbd5e1;
}

/* Responsivo para pantallas pequeñas */
@media (max-width: 768px) {
  .footer-content {
    grid-template-columns: 1fr;
    gap: 25px;
  }
  
  .social-links {
    flex-direction: row;
    flex-wrap: wrap;
    gap: 15px;
  }
  
  .footer-container {
    padding: 30px 15px 15px;
  }
}
</style>
<template>
  <div id="HalaMadrid">

    <section class="Bienvenida">
      <div class="BienvenidaTexto">
        <h1>¡Hala Madrid! Bienvenido</h1>
        <p>
          Explora la historia, las leyendas y el presente del club más grande del mundo.
          Con un palmarés inigualable de 14 Ligas de Campeones, el Real Madrid es un símbolo global de grandeza y éxito.
        </p>
      </div>
    </section>

    <img src="../assets/El mas grande de la historia.jpg" alt="">

    <section class="Noticias">
      <h2>Grandes Victorias</h2>
      <div class="NoticiasContenido">
        <p>
          El Real Madrid ha forjado su leyenda en el campo con victorias inolvidables y una mentalidad ganadora.
          Desde la época de Di Stéfano hasta la era moderna de la Champions League, cada título es una demostración de ambición y pasión.
        </p>
      </div>
    </section>

  </div>
</template>

<script>
export default {
  name: 'Contenido',
}
</script>

<style>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f0f2f5;
  color: #333;
}

#HalaMadrid {
  max-width: 1000px;
  margin: 0 auto;
  background-color: #fff;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
  color: #00529F; 
}


.Bienvenida {
  position: relative;
  text-align: center;
}


.BienvenidaTexto {
  padding: 40px 20px;
}


.Noticias {
  padding: 40px 20px;
  background-color: #f8f8f8;
  text-align: center;
}

.NoticiasContenido {
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap; 
  justify-content: center;
  margin-top: 20px;
}


.NoticiasContenido p {
  max-width: 500px; 
  text-align: left;
}
</style>
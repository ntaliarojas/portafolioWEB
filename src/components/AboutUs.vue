<template >

    <v-row id="about" justify="center" class="About" >
      <v-col lg="12" md="12" sm="12" xs="12" class="text-center">
        <div class="About-txt">
          <h3 class="about-text">SOBRE MI</h3>
          <p data-aos="fade-right" class="about-text2">Venga le Cuento</p>
          <p data-aos="fade-right" class="description">
            Soy una entusiasta del anime y la programación. 
            Me encanta parchar por Bogotá especialmente en bicicleta 
            durante las noches y pasar tiempo de calidad con mis amigos. 
            Disfruto de una buena comida y una linda vista, me gusta
            crear cosas simples y eficientes, y porsupuesto crear 
            recuerdos especiales en familia.
          </p>
          <div>
            <v-btn color="#7c3141" type="submit" elevation="8" class="button-cv" @click="descargarImagen">Descargar CV</v-btn>
          </div>
        </div>
      </v-col>
    </v-row>
  </template>
    
  <script>
  
  export default {
    name: 'AboutUs',
    methods: {
      descargarImagen() {
        const a = document.createElement('a');
        a.href = require('@/assets/CVN.jpg');
        a.download = 'CV-NATALIA.jpg'; // Puedes establecer un nombre de archivo personalizado
        a.style.display = 'none';
        document.body.appendChild(a);
        a.click();
        document.body.removeChild(a);
      }
    }
  };
  
  
  
  </script>
    
    
  <style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400&display=swap');
  
  
  /* Estilos para pantallas grandes (lg) */
  
  
  
  
  
  .About {
    padding-top: 9rem;
    position: relative;
    min-height: 40rem;
    background-repeat: repeat;
    text-align: center;
    border-bottom: 1px solid rgba(255, 255, 255, 0.449);
    border-top: 1px solid rgba(255, 255, 255, 0.449);
    background-color: #292929;
  
  
  }
  
  .About::after {
    bottom: 45%;
    content: "";
    position: absolute;
    left: 7%;
    width: 150px;
    height: 350px;
    background-image: url(../assets/puntos.png);
    background-size: contain;
  }
  
  .About::before {
    bottom: -0.1%;
    content: "";
    position: absolute;
    right: 7%;
    width: 150px;
    height: 350px;
    background-image: url(../assets/puntos.png);
    background-size: contain;
  }
  
  .about-text {
    font-family: 'Poppins', sans-serif;
    font-size: 9rem;
    line-height: 1;
    font-weight: bold;
    opacity: .1;
    color: white;
  }
  
  .about-text2 {
    font-family: 'Poppins', sans-serif;
    color: #7c3141;
    font-size: 2.5rem;
    margin: calc(-1rem - 2rem) auto 0 auto;
    line-height: 1.2;
    font-weight: bold;
  
  }
  
  
  .description {
    font-family: 'Poppins', sans-serif;
    color: #838383;
    font-size: 1.5rem;
    text-align: center;
    margin-top: 2rem;
    line-height: 1;
    padding-left: 60px;
    padding-right: 60px;
    margin-bottom: 3rem;
  
  }
  
  
  
  /* Estilos para pantallas medianas (md) */
  @media screen and (max-width: 409px) {
    .About::after {
      display: none;
    }
  
    .About::before {
      bottom: -0.1%;
      content: "";
      position: absolute;
      left: 7%;
      width: 150px;
      height: 150px;
      background-image: url(../assets/puntos.png);
      background-size: contain;
    }
  
    .About {
      padding-top: 3.5rem;
      position: relative;
      min-height: 25rem;
      background-repeat: repeat;
      text-align: center;
    }
  
    .about-text {
      font-size: 4rem;
    }
  
    .description {
  
      font-size: 1.2 rem;
      margin-top: 1rem;
    }
  
    .about-text2 {
      font-family: 'Poppins', sans-serif;
      font-size: 1.5rem;
      margin: calc(0.5rem - 2rem) auto 0 auto;
      line-height: 1.2;
  
    }
  }
  
  @media screen and (max-width: 417px) {
    .About {
      padding-top: 3rem;
      min-height: 33rem;
  
    }
  
    .About::after {
      display: none;
    }
  
    .About::before {
      display: none;
    }
  
    .about-text {
      font-size: 6rem;
    }
  
    .description {
      font-size: 1.1rem;
      margin-top: 1rem;
    }
  
  }
  
  @media screen and (max-width: 429px) {
    .about-text {
      font-size: 5rem;
    }
  
    .description {
      font-size: 1.2rem;
      margin-top: 1rem;
    }
  
    .About::after {
  
      width: 50px;
      bottom: 27%;
  
    }
  
    .About::before {
      display: none;
    }
  
    .About {
      padding-top: 4rem;
      min-height: 30rem;
      padding-bottom: 4rem;
  
    }
  }
  
  @media screen and (max-width: 645px) {
    .about-text {
      font-size: 6rem;
    }
  
    .description {
      font-size: 1.2rem;
      margin-top: 1rem;
    }
  
    .About::after {
  
      width: 50px;
      bottom: 33%;
  
    }
  
    .About::before {
      display: none;
    }
  
    .About {
      padding-top: 6rem;
      min-height: 33rem;
  
    }
  
  }
  
  @media screen and (max-width: 291px) {
    .About::after {
      display: none;
    }
  
    .About::before {
      display: none;
    }
  
    .About {
      padding-top: 3.5rem;
      min-height: 28rem;
      padding-bottom: 3rem;
  
    }
  
    .about-text {
      font-size: 4rem;
    }
  
    .description {
  
      font-size: 1rem;
      margin-top: 1rem;
    }
  
    .about-text2 {
      font-family: 'Poppins', sans-serif;
      font-size: 1.5rem;
      margin: calc(0.5rem - 2rem) auto 0 auto;
      line-height: 1.2;
  
    }
  }
  </style>
    
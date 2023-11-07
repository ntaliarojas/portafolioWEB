<template>
    <v-row id="portafolio" justify="center" class="Portafolio">
        <v-col lg="12" class="text-center">
            <h1 class="title-portfolio justify-center">Formación</h1>
        </v-col>

        <v-col lg="3" md="4" xl="3">
            <v-card data-aos="flip-left" data-aos-easing="ease-out-cubic" data-aos-duration="2000">
                <v-img src="../assets/sena.jpg" class="align-end" gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="250px" contain></v-img>
            </v-card>
            <div class="education-text-container">
                <p data-section="formacion">Analisis y Desarrollo de Sistemas </p>
                <p data-section="formacion" style="color: white;">"2021-2023"</p>
            </div>
        </v-col>

        <v-col lg="3" md="4" xl="3">
            <v-card data-aos="flip-left" data-aos-easing="ease-out-cubic" data-aos-duration="2000">
                <v-img src="../assets/unal.jpg" class="align-end" gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="250px" contain>
                </v-img>
            </v-card>

            <div class="education-text-container">
                <p data-section="formacion">Diseño de Aplicaciones Móviles</p>
                <p data-section="formacion" style="color: white;">"2023 - En curso"</p>
            </div>
        </v-col>
        <v-col lg="3" md="4" xl="3">
            <v-card data-aos="flip-left" data-aos-easing="ease-out-cubic" data-aos-duration="2000">
                <v-img src="../assets/ingles.png" class="align-end" gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="250px" contain></v-img>
            </v-card>
            <div class="education-text-container">
                <p data-section="formacion">Competencia Ingles básica limitada</p>
                <p data-section="formacion" style="color: white;">"2023 - En curso"</p>
            </div>
        </v-col>


    </v-row>
</template>
  
<script>
export default {
    name: "EducatioMe"

};
</script>
  
<style scoped>
.Portafolio {
    position: relative;
    background-repeat: repeat;
    text-align: center;
    min-height: 40rem;
    padding: 2rem;
    color: white;
    background-color: #1F1F1F;


}




.title-portfolio {
    font-family: 'Poppins', sans-serif;
    font-size: 3.5rem;
    padding: 20px;
    margin-top: 1rem;
}


@media screen and (max-width: 391px) {
    .title-portfolio {
        font-family: 'Poppins', sans-serif;
        font-size: 2.5rem;

    }


}
</style>
  
<template>
    <v-row id="portafolio" justify="center" class="Portafolio">
        <v-col lg="12" class="text-center">
            <h1 class="title-portfolio justify-center">Portafolio</h1>
        </v-col>

        <v-col lg="3" md="4" xl="3" >
            <v-card data-aos="flip-left" data-aos-easing="ease-out-cubic" data-aos-duration="2000">
                <v-img src="../assets/2.jpg" class="align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)" height="200px" cover></v-img>
                <v-card-title><a style="color: #7c3141; text-decoration: none;" href="https://github.com/ntaliarojas/FRONT">FRONT</a></v-card-title>
            </v-card>
        </v-col>

        <v-col lg="3" md="4" xl="3" >
            <v-card data-aos="flip-left" data-aos-easing="ease-out-cubic" data-aos-duration="2000">
                <v-img src="../assets/3.jpg" class="align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)" height="200px" cover></v-img>
                <v-card-title><a style="color: #7c3141; text-decoration: none;" href="https://github.com/ntaliarojas/FRONT">SQL</a></v-card-title>
            </v-card>
        </v-col>
        <v-col lg="3" md="4" xl="3" >
            <v-card data-aos="flip-left" data-aos-easing="ease-out-cubic" data-aos-duration="2000">
                <v-img src="../assets/1.jpg" class="align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)" height="200px" cover></v-img>
                <v-card-title><a style="color: #7c3141;  text-decoration: none;"  target="_blank" href="https://github.com/ntaliarojas/DesarrolloWeb">DESARROLLO WEB</a></v-card-title>
            </v-card>
        </v-col>
   

    </v-row>


</template>
  
<script>
export default {
    name: "PortafolioMe"
  
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
  
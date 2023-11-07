<template>
    <v-row class="contac" id="contacto">
        <!-- Primera columna -->
        <v-col class="container-txt mt-4" cols="12" md="6" sm="12" xs="12">
            <v-row>
                <v-col cols="12">
                    <div class="container-vconectar">
                        <h4 data-aos="fade-right" class="txt-vconectar">Vamos a Conectar</h4> <br>
                    </div>
                    <p data-aos="fade-right" class="txt-conectemos" xs="12">Conectemos Ideas & Oportunidades
                        <v-divider></v-divider>
                    </p>
                    <br>
                    <p data-aos="fade-right" class="p-conectmos" style="color: white;">Estoy en búsqueda de nuevas oportunidades
                        laborales,
                        encantada de ofrecer mi experiencia y
                        habilidades para explorar posibles colaboraciones.
                    </p>
                </v-col>
                <v-col lg="12">
                    
                    <h4 data-aos="fade-right" class="txt-vconectar">Redes sociales</h4> <br>
                </v-col>

                <v-col data-aos="fade-right" class="redesS d-flex justify-star">
                    <v-btn color="blue" elevation="8" class=" mr-2"><a
                            href="https://www.linkedin.com/in/natalia-rojas-puertas/" target="_blank"
                            rel="noopener noreferrer">linkedIn</a></v-btn>
                    <v-btn color="black" type="submit" elevation="8" class="mr-2"><a href="https://github.com/ntaliarojas"
                            target="_blank" rel="noopener noreferrer">Git hub</a></v-btn>
                </v-col>
            </v-row>
        </v-col>


        <!-- Segunda columna -->
           
            <v-col data-aos="zoom-in" class="formulario mt-7" md="6" sm="12" xs="12">
            <v-card class="formulario-card transparent-card">
                <v-card-title class="text-h5 card_">
                    Formulario de Envío
                </v-card-title>
                <v-card-text>
                    <form class="transparent-card" action="https://formsubmit.co/llerlynatisrojaspuertas@gmail.com" method="POST">
                       
                        <v-text-field name="name" type="name" label="Nombre" required></v-text-field>
                        <v-text-field label="Correo" type="email" for="email" name="email" required></v-text-field>
                        <v-textarea label="Mensaje"  name="mensaje" cols="15" rows="8" required></v-textarea>
                        <v-btn color="#7c3141" type="submit">Enviar</v-btn>
                    
                    
                    
                <input type="hidden" name="_next" value="http://localhost:8081/">
                <input type="hidden" name="_captcha" value="false">
                    </form>
                </v-card-text>
            </v-card>
        </v-col>
           
           
           
           
   
    </v-row>
</template>
  

<script>

export default {
    name: 'contactaMe'


}
</script>



<style scoped>
.contac {
    position: relative;
    background-repeat: repeat;
    border-top: 1px solid rgba(255, 255, 255, 0.449);
    background-color: #292929;
    padding-right: 4rem;
    padding-left: 4rem;
    padding-top: 3rem;

}

.txt-vconectar {
    font-family: 'Poppins', sans-serif;
    font-size: 1.5rem;
    line-height: 1;
    font-weight: bold;
    color: #838383;
    margin: 0 auto;
}

.txt-conectemos {
    font-family: 'Poppins', sans-serif;
    font-size: 4rem;
    line-height: 1;
    font-weight: bold;
    max-width: 100%;
    /* Para que el texto no se desborde si es muy largo */
    word-wrap: break-word;
    /* Romper palabras largas si es necesario */
    color: #7c3141;
}

.transparent-card {
    background-color: #1F1F1F;
    /* Color verde con opacidad */
    box-shadow: none;
    color: #838383;
}

.redesS a {
    text-decoration: none;
    color: white;
}

@media screen and (max-width: 376px) {
    .txt-conectemos {
        font-size: 2rem;

    }

    .p-conectmos {
        display: none;
    }

    .contac {
        padding: 1rem;

    }
}

@media screen and (max-width: 450px) {
    .txt-conectemos {
        font-size: 3rem;

    }

    .p-conectmos {
        display: none;
    }

    .contac {
        padding: 1rem;

    }
}
</style>
<template>
    <v-row class="Skills">

        <v-col lg="12">
            <h1 class="title-sk" data-aos="fade-right" >Habilidades</h1>

            <v-row class="skill-icons-container">
                <v-col lg="1" md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/icon-html.png">
                        </v-img>
                        <p class="text-center">HTML 5</p>
                    </v-card>
                </v-col>

                <v-col lg="2" md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/icon-css.png"></v-img>
                        <p class="text-center">CSS 3</p>
                    </v-card>
                </v-col>

                <v-col lg="1"  md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/logo.svg"></v-img>
                        <p class="text-center">Vue.js</p>

                    </v-card>
                    
                </v-col>
                <v-col lg="2"  md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/icon-js.png"></v-img>
                        <p class="text-center">JavaScript</p>

                    </v-card>
                </v-col>

                <v-col lg="1"  md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/laravel.png"></v-img>
                        <p class="text-center">Laravel</p>
                    </v-card>
                </v-col>

                <v-col lg="2"  md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/php.png"></v-img>
                        <p class="text-center">PHP</p>

                    </v-card>
                   
                </v-col>

                <v-col lg="1"  md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/icon-git.png"></v-img>
                        <p class="text-center">Git</p>
                    </v-card>
                </v-col>
                <v-col lg="2"  md="3" sm="3">
                    <v-card  data-aos="zoom-in" class="icon-sk">
                        <v-img class="img" src="../assets/figma.png"></v-img>
                        <p class="text-center">Figma</p>
                    </v-card>
                </v-col>
            </v-row>
        </v-col>
    </v-row>
</template>
  
<script>

export default {
    name: 'SkillsMe',
    
}
</script>
  
  
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400&display=swap');



* {
    color: white;
    margin-left: 0;

}

.Skills {
    background-color: #292929;
    position: relative;
    min-height: 15rem;
    background-repeat: repeat;
    border-bottom: 1px solid rgba(255, 255, 255, 0.449);
    border-top: 1px solid rgba(255, 255, 255, 0.449);
    padding-bottom: 5rem;

}

.skill-icons-container p{
    font-size: 0.9rem;
    margin-top: -0.3rem;
    font-family: 'Poppins', sans-serif;

}
.skill-icons-container .img{
    padding-top: 1.5rem;
    width: 6rem;
    margin: 0 auto;

}
.icon-sk {
    width: 7.9rem;
    height: 8.8rem;
    transition: 0.4s;
    border-radius: 20px;
    background-color: #1F1F1F;;
    margin: 0 auto;
}

.title-sk {
    margin-top: 5rem;
    color: white;
    font-family: 'Poppins', sans-serif;
    font-size: 3rem;
    margin-bottom: 5rem;
    text-align: center;
    font-weight: bold;

}

@media screen and (max-width: 391px) {
    .title-sk {
        color: #aaffaa;
        font-family: 'Poppins', sans-serif;
        font-size: 2rem;
        text-align: center;
    }
    .Skills {
    padding-bottom: 10rem;
    min-height: 10rem;

   
}
}
</style>
  
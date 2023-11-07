<template>
    <v-row  class="About">
      <v-footer class="fotter text-center d-flex flex-column">
                  <div>
                      {{ new Date().getFullYear() }} — <strong>Copyright © | Coded with &hearts; by Natalia Rojas</strong>
                  </div>
              </v-footer>
              </v-row>
  
  
  </template>
  <script>
  
  export default {
      name: 'footerMe'
  
  
  }
  </script>
  
  <style scoped>
    * {
      color: white;
      margin-left: 0;
     
    }
  .fotter {
      position: relative;
      background-color: #1F1F1F;
      background-repeat: repeat;
      text-align: center;
  }
  
  </style>
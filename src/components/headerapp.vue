<template>
  <v-app-bar class="transparent-nav" style="background-color: transparent;
            backdrop-filter: blur(10px);
            position: fixed;

        ">
    <v-app-bar-title style="color: white;">
      <v-icon>
        <img src="@/assets/butterfly.png" alt="Mariposa" style="width: 24px; height: 24px;" />
      </v-icon>
      Portafolio
    </v-app-bar-title>
    <v-list class="nave d-flex align-center" style="background-color: transparent;
      color: white;
      ">
      <v-list-item>
        <v-list-item-title class="list">
          <v-btn href="#inicio">Inicio</v-btn>
          <v-btn href="#about">Sobre mi</v-btn>
          <v-btn href="#Formacion">Formación</v-btn>
          <v-btn href="#portafolio">Portafolio</v-btn>
          <v-btn href="#contacto">Contacto</v-btn>
        </v-list-item-title>
      </v-list-item>
    </v-list>

    <v-menu class="menu">
      <template v-slot:activator="{ props }">
        <v-btn icon="mdi-dots-vertical" v-bind="props"></v-btn>
      </template>

      <v-list>
        <v-list-item v-for="(item, i) in items" :key="i">
          <v-list-item-title>{{ item.title }}</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-menu>
  </v-app-bar>
</template>
  
<script>
export default {
  name: 'headerapp',
  data: () => ({
    items: [
      { title: 'Click Me' },
      { title: 'Click Me' },
      { title: 'Click Me' },
      { title: 'Click Me 2' },
    ],
  }),
}
</script>
<style scoped>
.list:hover {
  color: #d9506d;
}

@media screen and (max-width: 800px) {
  .list {
    visibility: hidden;
    /* Oculta el elemento */
    height: 0;
    /* Reduce la altura a 0 para eliminar el espacio */

  }
}
</style>
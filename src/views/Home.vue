<template>
  <v-app>
    <v-main class="main" style="background-color: #1F1F1F;">
      <headerapp />
      <HelloWorld />
      <AboutUs />
      <EducationMe />

      <SkillsMe />
      <PortafolioMe />

      <ContactaMe />
      <footerMe />




    </v-main>
  </v-app>
</template>

<script>
import AboutUs from '@/components/AboutUs.vue';
import EducationMe from '@/components/EducationMe.vue';
import HelloWorld from '@/components/HelloWorld.vue';
import PortafolioMe from '@/components/PortafolioMe.vue';
import ContactaMe from '@/components/contactaMe.vue';
import Headerapp from '@/components/headerapp.vue';
import SkillsMe from '@/components/SkillsMe.vue';
import FooterMe from '@/components/footerMe.vue';







export default {
  name: 'Home',
  data: () => ({
    //
  }),
  components: { AboutUs, ContactaMe, EducationMe, Headerapp, HelloWorld, PortafolioMe, SkillsMe, FooterMe }
}
</script>
<style scoped>



</style>
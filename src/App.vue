<template>
  <v-app>
    <Nav /> 
    <v-main>
     
        <HelloWorld />
      
    
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Nav from './components/Nav.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
    Nav,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>

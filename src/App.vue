<template>
  <v-app>
    <Toolbar></Toolbar>
    <v-main>
    <home-page></home-page>
    </v-main>
    <Footer></Footer>
  </v-app>
</template>

<script>
import HomePage from './components/HomePage';
import Toolbar from './components//Toolbar.vue';
import Footer from './components/Footer.vue';


export default {
  name: 'App',

  components: {
    HomePage,
    Toolbar,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>

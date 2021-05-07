<template>
  <v-app>
    <p-toolbar/>
    <v-main>
      <!-- <HelloWorld/> -->
      <router-view /> 
    </v-main>
  </v-app>
</template>

<script>
import PToolbar from './components/PToolbar';
// import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    // HelloWorld,
    PToolbar,
  },

  data: () => ({
    //
  }),
};
</script>
<style>



</style>
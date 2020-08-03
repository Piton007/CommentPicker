<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark

    >
      Comment Picker
    </v-app-bar>
    <v-main>
      <v-container fluid>
        <stepper/>
      </v-container>
    </v-main>
    <v-footer app>
      <div class="footer">
        Copyright&#169; 2020 
      </div>
     
  </v-footer>
  </v-app>
</template>

<script>
import Stepper from './components/Stepper';

export default {
  name: 'App',

  components: {
    "stepper":Stepper,
  },

  data: () => ({
    //
  }),
};
</script>
<style scoped>
  .footer {
    width: 100%;
    text-align: center !important;
  }
</style>

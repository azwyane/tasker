<template>
  <v-app id="inspire">
    
    
    <Drawer/>    
    
    <Topbar/>

    <v-main>
      <v-container
        class="fill-height"
        fluid
      >
        <v-row
          align="center"
          justify="center"
        >
          <v-tooltip right>
            
            <span>Source</span>
          </v-tooltip>
        </v-row>
      </v-container>
    </v-main>


    <v-btn
      bottom
      color="pink"
      dark
      fab
      fixed
      right
      @click="dialog = !dialog"
    >
      <v-icon>mdi-plus</v-icon>
    </v-btn>


    <Form/>


  </v-app>
</template>



<script>
import Form from './components/Form';
import Topbar from  './components/Topbar';
import Drawer from './components/Drawer';

export default {
  name: 'App',

  components: {
    Form,
    Topbar,
    Drawer,
  },

  data: () => ({
    //
  }),
};
</script>

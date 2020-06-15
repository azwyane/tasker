<template>
    <v-navigation-drawer
      v-model="drawer"
      app
    >
     

    </v-navigation-drawer>
</template>


<script>
export default {
    name : "Drawer",
    props: {
    source: String,
  },
  data: () => ({
    dialog: false,
    drawer: null,
  }),
  
}
</script>
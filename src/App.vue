<template>
  <v-app>
    <v-app-bar
      app
      dark
    >
      <div class="d-flex align-center">
        Logo
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Settings</span>
        <v-icon>mdi-wrench</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <v-container class="">
        <index-list></index-list>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>


import IndexList from "./components/Main/IndexList";
export default {
  name: 'App',

  components: {
    IndexList

  },

  data: () => ({
    //
  }),
};
</script>

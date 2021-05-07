<template>
    <v-app-bar
      app
      color="black"
      dark
    >

      <v-spacer></v-spacer>
      <v-toolbar-items>
          <v-btn text @click="$vuetify.goTo('#about')">about</v-btn>
          <v-btn text @click="$vuetify.goTo('#portfolio')">portfolio</v-btn>
          <v-btn text @click="$vuetify.goTo('#contact')">contact</v-btn>

      </v-toolbar-items>

    </v-app-bar>
</template>

<script>
export default {

}

</script>

<style>

</style>

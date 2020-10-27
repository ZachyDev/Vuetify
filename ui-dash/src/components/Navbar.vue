<template>
  <nav>
      <v-toolbar  app>
          <v-toolbar-title class="text-uppercase grey--text">
              <span class="font-weight-light">Record.</span>
              <span>me!</span>
          </v-toolbar-title>
         <v-spacer></v-spacer>
          <v-btn color="grey">
              <span>Sign Out</span>
              <v-icon right>mdi-logout-variant</v-icon>
          </v-btn>
      </v-toolbar>
  </nav>
</template>

<script>
export default {
    name: "Navbar"
}
</script>

<style>

</style>
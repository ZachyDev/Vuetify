<template>
  <nav>
      <v-toolbar 
      dark 
      height="100" 
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg">
    
        <!-- toolbar icon -->
         <v-app-bar-nav-icon @click="toogleSideNav"></v-app-bar-nav-icon>

          <!-- toolbar title -->
          <v-toolbar-title class="text-uppercase grey--text">
              <span class="font-weight-light">Record.</span>
              <span>me!</span>
          </v-toolbar-title>
          <!-- toolbar title end -->

         <v-spacer></v-spacer>
         
         <!-- Toolbar btn -->
          <v-btn color="grey">
              <span>Sign Out</span>
              <v-icon right>mdi-export</v-icon>
          </v-btn>
          <!-- Toolbar btn end -->

      </v-toolbar>
      <!-- v-toolbar end -->

    <!-- navigational drawer -->
    <v-navigation-drawer
        v-model="drawer" 
        app 
        color="deep-purple accent-4">
        Test
    </v-navigation-drawer>
  </nav>
</template>

<script>
export default {
    name: "Navbar",
    data() {
        return {
            drawer: false
        }
    },
    methods: {
        toogleSideNav() {
            return this.drawer = !this.drawer;
        }
    }
}
</script>

<style>

</style>
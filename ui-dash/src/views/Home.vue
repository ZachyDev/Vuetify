<template>
  <div class="home">
    <h1>Homepage</h1>
    <v-btn class="success white--text">
      <v-icon left>mdi-github</v-icon>
      <span>Github</span>
    </v-btn>

    <v-btn class="success white--text">
      <span>Github</span>
      <v-icon right large>mdi-twitter</v-icon>
    </v-btn>

    <v-btn fab small dark color="purple" white>
      <v-icon >mdi-twitter</v-icon>
    </v-btn>

  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  
  }
}
</script>

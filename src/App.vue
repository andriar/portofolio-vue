<template>
  <v-app id="app">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <router-view />
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",

  components: {},

  data: () => ({
    //
  })
});
</script>

<style lang="scss" src="./assets/global.scss"></style>

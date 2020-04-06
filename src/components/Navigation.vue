<template>
  <div id="nav">
    <router-link class="child" to="/">Home</router-link>
    <router-link class="child" to="/about">About</router-link>
    <router-link class="child" to="/about">Shit !</router-link>
  </div>
  <!-- <div id="nav-mobile" justify-end>
    <v-btn text large depressed>
      <v-icon color="white">mdi-menu</v-icon>
    </v-btn>
  </div>-->
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class Navigation extends Vue {
  // @Prop() private msg!: string;
}
</script>

<template>
  <v-app>
    <v-main>
      <Home/>
    </v-main>
    <v-footer
    class="bg-blue-500"
    padless
  >
    <v-row
      justify="center"
      no-gutters
    >
      <v-col
        class="bg-blue-500 py-4 text-center white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Gravity: Unknown made with <span class="text-red-500">❤</span> by Marc vd Made</strong>
      </v-col>
    </v-row>
  </v-footer>
  </v-app>
</template>

<script>
import Home from './components/Home';

export default {
  name: 'App',

  components: {
    Home,
  },

  data: () => ({
    //
  }),
};
</script>

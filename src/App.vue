<template>
  <v-app>
    <v-main>
      <!-- <HelloWorld/> -->
      <Game />
    </v-main>
  </v-app>
</template>

<script>
import Game from './Game.vue'

export default {
  name: 'App',

  components: {
    Game,
  },

  data: () => ({
    //
  }),
}
</script>

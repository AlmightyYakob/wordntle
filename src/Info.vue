<script setup lang="ts">
</script>

<template>
  <v-card>
    <v-card-text>
      Guess the <strong>WORDN'TLE</strong> in six tries.<br><br>

      Each guess must be a fake 5 letter word.
      All answers are grammatically plausible english words, and aren't just a string of 5 random characters like <code>ikghj</code>.
      An example of a valid answer is <code>shamp</code>. Hit the enter button to submit.<br><br>

      After each guess, the color of the tiles will change to show how close your guess was to the word.
    </v-card-text>
  </v-card>
</template>

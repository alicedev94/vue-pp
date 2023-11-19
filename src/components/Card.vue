<template>
  <v-row align="center" justify="center">
    <v-col cols="auto">
      <v-card
        class="mx-auto mt-5"
        max-width="344"
        title="User"
        subtitle="user@example.com"
        prepend-icon="mdi-account"
        append-icon="mdi-check"
      >
        <v-card-text
          >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod.
        </v-card-text>
        <v-btn @click="routerToHome">Home</v-btn>
        <v-btn @click="routerToAbout">About</v-btn>
      </v-card>
    </v-col>
  </v-row>
</template>

<script setup>
// router
const routerToHome = () => (window.location.href = "/");
const routerToAbout = () => (window.location.href = "/About");
</script>

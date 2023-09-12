<template>
  <v-app-bar app color="#111111" dark flat class="px-8">
    <v-btn icon>
      <v-icon color="#958b00">mdi-heart</v-icon>
    </v-btn>

    <v-spacer></v-spacer>
    <v-btn text @click="scroll('Home')">Home</v-btn>
    <v-btn text @click="scroll('Introduction')">Introduction</v-btn>
    <v-btn text @click="scroll('About')">About</v-btn>
    <v-btn text @click="scroll('Contact')">Contact</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style></style>
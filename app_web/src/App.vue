<template>
  <v-app>
    <v-app-bar app color="primary">
      <v-app-bar-title>
        <span class="display-1">ACME STUDIO</span>
        <v-divider inset vertical class="mx-1"></v-divider>
        <span>Learning center</span>
      </v-app-bar-title>
      <v-spacer></v-spacer>
      <v-btn plain to="/home" color="white">HOME</v-btn>
      <v-btn plain to="/Posts" color="white">Posts</v-btn>
      <v-btn plain to="/about" color="white">ABOUT</v-btn>
    </v-app-bar>
    <v-main>
      <v-container fluid>
        <router-view/>
      </v-container>
    </v-main>
  </v-app>
</template>

<style>

</style>

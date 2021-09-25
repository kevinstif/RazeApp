<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div>
      <v-img :src="require('./img/Logo.png')"/>
      </div>
      <v-spacer></v-spacer>
      <h3 >User Name</h3>
      <v-btn icon>
        <v-img  class="" src="#"></v-img>
      </v-btn>
    </v-app-bar>

    <v-main>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data: () => ({

  }),
};
</script>

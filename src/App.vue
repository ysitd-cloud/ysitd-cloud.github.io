<template>
  <v-app light>
    <toolbar />
    <main>
      <v-content>
        <v-container fluid>
          <main-content />
        </v-container>
      </v-content>
    </main>
    <v-footer fixed app>
      <span>&copy; 2017 YSITD Cloud</span>
    </v-footer>
  </v-app>
</template>

<script>
  import Toolbar from './components/Toolbar.vue';
  import MainContent from './components/Content.vue';

  export default {
    name: 'app',
    components: {
      Toolbar,
      MainContent,
    },
  };
</script>

<style lang="stylus">
  @import "../node_modules/vuetify/src/stylus/settings/_colors.styl"
  $theme := {
        primary: #44A148
        accent: $cyan.lighten-2
        secondary: $indigo.darken-2
        info: $blue.base
        warning: $amber.base
        error: $red.base
        success: $green.base
    }
  @import "../node_modules/vuetify/src/stylus/main.styl"
</style>

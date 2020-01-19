<template>
  <v-app>
    <v-content class="grey darken-4">
      <Toolbar/>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import Toolbar from './components/Toolbar';

export default {
  name: 'App',

  components: {
    Toolbar
    
  },

  data: () => ({
    //
  }),
};
</script>

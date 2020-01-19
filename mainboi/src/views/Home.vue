<template>
  <div class="home">
    <v-row align="start" justify="space-around" no-gutters>
      <h1>Welcome to my website!</h1>
    </v-row>
      <h3 class="centered">The goal of this website is to provide me with 
        a space to store and view everything I've coded. But also to help me
        manage all I that have to do and have done.
        <br/> As you may be able to tell there's nothing here, 
        but I'm working on it and there's a lot to do!
      </h3>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {

  }
}
</script>

<style>
  .centered {
    display: block;
    width: 100%;
    max-width: 450px;
    margin: 0 auto;
  }
  h3{
    color:white;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
  }
  h1{
    color:whitesmoke;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    text-decoration: underline;
  }
</style>

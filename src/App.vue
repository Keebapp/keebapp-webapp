<template>
  <div class="logo_container">
    <img class="logo" alt="keeb logo" src="./assets/logo.svg">
  </div>
  <h1>
    Keebapp Webapp
  </h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'App',
  components: {}
});
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  .logo_container{
    margin: 0px auto;
    width: 200px;
    background-color: #8DA5A8;
    box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.5);
    border-radius: 1rem;
    img.logo {
      filter: drop-shadow(3px 3px 5px rgba(0, 0, 0, 0.25));
    }
  }
  
}
</style>

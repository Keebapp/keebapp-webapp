<template>
  <img class="logo" alt="keeb logo" src="./assets/logo.png">
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
  img.logo {
    border-radius: 1rem;
    box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.5);
  }
}

</style>

<template>
  <div id="app">
    <AppTitle/>
    <NewComponent/>
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import NewComponent from './components/NewComponent.vue';

export default {
  name: 'App',
  components: {
    AppTitle,
    NewComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

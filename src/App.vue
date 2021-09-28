<template>
  <div id="app">
    <hero />
    <Title msg="Primo esercizio con i componenti" />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import hero from './components/hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    hero
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

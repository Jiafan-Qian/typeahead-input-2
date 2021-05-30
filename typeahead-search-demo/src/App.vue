<template>
  <div id="app">
    <h1>small typeahead suggestion input for all American states and territories</h1>
    <TypeAheadInput />
  </div>
</template>

<script>
import TypeAheadInput from './components/TypeAheadInput.vue'

export default {
  name: 'App',
  components: { TypeAheadInput }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
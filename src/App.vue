<template>
  <div id="app">
   <Bpmn />
  </div>
</template>

<script>
import Bpmn from './components/VueBpmn/index'

export default {
  name: 'App',
  components: {
    Bpmn
  }
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

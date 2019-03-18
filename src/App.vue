<template>
  <div id="app">
    <Entry title="Online" time_period="2015-2019" role="Medlem" description="insert description here"/>
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Entry from './components/Entry.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
    Entry
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

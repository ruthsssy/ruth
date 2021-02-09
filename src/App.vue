<template>
  <div id="app">
      <Department msg="Ruth Navarro Iglesias"/>
  </div>
</template>

<script>
import Department from './components/Department.vue'

export default {
  name: 'App',
  components: {
    Department
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
   color: #2c3e50;
}
</style>

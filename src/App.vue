<template>
  <MyCalculadora />
</template>

<script>
import MyCalculadora from './components/MyCalculadora.vue'

export default {
  name: 'App',
  components: {
    MyCalculadora
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

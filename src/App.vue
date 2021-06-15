<template>
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import stream from 'getstream';

// instantiate a new client (server side)
// const client = stream.connect(
//   '',
//   ''
// );

export default {
  components: {
    HelloWorld
  },
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: fuchsia;
  margin-top: 60px;
}
</style>

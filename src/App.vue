<template>
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import { viteCommonjs } from '@originjs/vite-plugin-commonjs'
import 'getstream';

// instantiate a new client (server side)
// const client = stream.connect(
//   '92mzjgtz5tvc',
//   'pbrxdneuga6wxswydvkvhrhmmher4yhpbmtjeudj3f5pm4chquwmveu4jmb23xqd'
// );

export default {
  components: {
    HelloWorld
  },
}

    // const client = stream.connect(
    //   '92mzjgtz5tvc',
    //   'pbrxdneuga6wxswydvkvhrhmmher4yhpbmtjeudj3f5pm4chquwmveu4jmb23xqd'
    // );

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
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

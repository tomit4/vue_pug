<template lang="pug">
body
  img(alt="Vue logo" src="./assets/logo.png")
  HelloWorld(msg="Welcome to Vue with Pug!")
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
body {
  background-color: #1e1e1e;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #e0b24d;
  margin-top: 40px;
}
</style>

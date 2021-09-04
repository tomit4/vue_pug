<template lang="pug">
body
  div.hello
  h1 {{msg}}
  p.
    For a guide and recipes on how to configure / customize this project,
    check out the 
  a(href="https://cli.vuejs.org" target="_blank" rel="noopener") vue-cli documentation
  br
  br
  a(href="https://vue-loader.vuejs.org/guide/pre-processors.html#pug" target="_blank" rel="noopener") vue-pug setup
  h3 Essential Links
  ul
    li
      a(href="https://vuejs.org" target="_blank" rel="noopener") Vue Docs
    li
      a(href="https://forum.vuejs.org" target="_blank" rel="noopener") Forum
    li
      a(href="https://news.vuejs.org" target="_blank" rel="noopener") News
  h3 Ecosystem
  ul
    li
      a(href="https://router.vuejs.org" target="_blank" rel="noopener") vue-router
    li
      a(href="https://vuex.vuejs.org" target="_blank" rel="noopener") vuex
    li
      a(href="https://vitejs.dev/" target="_blank" rel="noopener") vite
    li
      a(href="https://nuxtjs.org/" target="_blank" rel="noopener") nuxt
    li
      a(href="https://vuetifyjs.com/en/" target="_blank" rel="noopener") vuetify
    li
      a(href="https://github.com/vuejs/petite-vue" target="_blank" rel="noopener") petite-vue
  h3 Pug Docs/Tutorial
  ul
    li
      a(href="https://pugjs.org/api/getting-started.html" target="_blank" rel="noopener") Pug Docs
    li
      a(href="https://www.youtube.com/watch?v=kt3cEjjkCZA" target="_blank" rel="noopener") FCC Tutorial
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
body {
  background-color: #1e1e1e;
}
h3 {
  color: #e0b24d;
  margin: 20px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 7px;
}
a {
  color: #42b983;
}
</style>

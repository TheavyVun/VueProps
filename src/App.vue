<template>
  <nav-view />
  <content-view />
  <footer-view />
</template>

<script>
import Nav from './components/navbar/NavbarView.vue'
import Content from './components/content/ContentView.vue'
import Footer from './components/footer/FooterView.vue'

export default {
  components: {
    "nav-view": Nav,
    "content-view": Content,
    "footer-view": Footer,
  }
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}
#app {
  display: flex;
  height: 100vh;
  flex-direction: column;
}
</style>

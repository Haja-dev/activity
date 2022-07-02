<template>
  <div id="app">
    <WebsiteHeader />
  </div>
</template>

<script>
import WebsiteHeader from './components/WebsiteHeader.vue'

export default {
  name: 'App',
  components: {
    WebsiteHeader
  }
}
</script>

<style>
#app {
  font-family: 'Finlandica', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
h1, h2, h3, h4 {
  font-family: 'Holtwood One SC', serif;
}
</style>

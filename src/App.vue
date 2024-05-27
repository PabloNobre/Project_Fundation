<template>
  <HeaderPage/>
  <HomePage/>
  <FooterPage/>
</template>

<script>
import HomePage from './components/Home.vue'
import HeaderPage from './components/Header.vue'
import FooterPage from "./components/Footer.vue";

export default {
  name: 'App',
  components: {
    HomePage,
    HeaderPage,
    FooterPage,
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

<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <AppHeader/>
  <AppBody/>
  <AppFooter/>
</template>

<script>
import AppBody from './components/AppBody'
import AppHeader from './components/AppHeader'
import AppFooter from './components/AppFooter'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppBody,
    AppFooter,
  }
};
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

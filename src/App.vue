<template>
  <div id="app">
    <header>
      <img class="logo" src="./assets/images/logo.png" alt="logo">
    </header>
    <MainTable/>
  </div>
</template>

<script>
import MainTable from './components/MainTable'

export default {
  name: 'App',
  components: {
    MainTable
  },
}
</script>

<style lang="scss">
@import './assets/styles/custom-bootstrap.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';

html, body {
  height: 100%;
  margin: 0;
  background: #333;
  background: -webkit-linear-gradient(left top, #30cfd0, #330867);
  background:    -moz-linear-gradient(bottom right, #30cfd0, #330867);
  background:         linear-gradient(to bottom right, #30cfd0, #330867);
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;

  header {
    margin-bottom: 20px;
    
    .logo {
      max-width: 200px;
      padding: 15px 0 0 20px;
    }
  }
}
</style>

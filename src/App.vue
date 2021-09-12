<template>
  <Header name="HOANG Minh Chau" profession="Web Developper"/>
  <About title="About me"/>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    Header,
    About
  }
}
</script>

<style>

  body {
    margin: 0;
  }

  #app {

    font-family: 'Raleway', sans-serif;
    
  }

</style>

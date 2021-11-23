<template>
  <div id="app">
    <Hero/>
    <div id="page">
      <img alt="Vue logo" src="./assets/logo.png">
      <Title/>
    </div>
    
    
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/>     Pagina di base di vue-->
  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero,
    /* HelloWorld, */
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}

#page {
  position: relative;
}

</style>

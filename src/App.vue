<template>
  <div id="app">
    <MyVueProject />
    <TextTest />
  </div>
</template>

<script>
import MyVueProject from './components/MyVueProject.vue'
import TextTest from './components/TextTest.vue'

export default {
  name: 'App',
  components: {
    MyVueProject,
    TextTest
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

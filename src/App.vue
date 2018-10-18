<template>
  <div id="app">
    <h1>Demo for the app</h1>
    This repository is an example for a medium post on how to create a 
    vue component for the community.<br/>
    This post will walk you through the process of creating a npm ready
    js package, and make a demo website using Github Pages.
    <a href="">Have a look at the post here</a>
    <h2>The component itself</h2>
    <my-component/>
  </div>
</template>

<script>
import MyComponent from './components/MyComponent.vue'

export default {
  name: 'app',
  components: {
    MyComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

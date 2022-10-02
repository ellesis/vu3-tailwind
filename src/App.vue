<template>
  <div class="flex flex-col justify-center bg-yellow-300 items-center h-screen">
    <h1 className="text-3xl font-bold underline">Hello world!</h1>
    <div class="text-4xl">Hello 👋🏼 Font Awesome</div>
    <div><font-awesome-icon icon="fa-solid fa-user-secret" /></div>
  </div>
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
  import HelloWorld from './components/HelloWorld.vue'

  export default {
    name: 'App',
    components: {
      HelloWorld
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

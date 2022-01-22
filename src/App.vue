<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <h2>This is my second change that i want tell to Git!</h2>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import NewBranch from "./components/NewBranch.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    NewBranch,
  },
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

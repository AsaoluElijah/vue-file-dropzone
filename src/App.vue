<template>
  <div id="app">
    <DropFile />
  </div>
</template>

<script>
import DropFile from "./components/DropFile.vue";
export default {
  name: "App",
  components: {
    DropFile,
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
}
</style>

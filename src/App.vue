<template>
  <div id="app">
    <navigation></navigation>
    <router-view />
  </div>
</template>

<script>
import Navigation from "./components/navigation";

export default {
  name: "App",
  components: {
    Navigation
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  /* color: #2c3e50; */
  margin: 0;
}
body {
  margin: 0;
}
/* styles */
* {
  margin: 0;
  padding: 0;
}

*,
:after,
:before {
  box-sizing: border-box;
}

body {
  background-color: #e2e2e2;
}
</style>

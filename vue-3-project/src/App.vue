<template>
  <div id="app">
    <Profile />
  </div>
</template>

<script>
import Profile from "./components/Profile";

export default {
  name: "App",
  components: {
    Profile,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  background-color: #f3f5fa;
  min-height: 100vh;
}
</style>

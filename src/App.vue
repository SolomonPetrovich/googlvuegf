<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="25%" />
    <GoogleLoginComponent></GoogleLoginComponent>
  </div>
</template>

<script>
import GoogleLoginComponent from "./components/GoogleLoginComponent";

export default {
  name: "App",
  components: {
    GoogleLoginComponent,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

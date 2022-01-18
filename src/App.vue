<template>
  <div id="app">
    <Header />
    <Main />
    <ServiceSolution />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import ServiceSolution from "./components/ServiceSolution.vue";


export default {
  name: "App",
  components: {
    Header,
    Main,
    ServiceSolution,
  },
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: sans-serif;
  background-color: white;
}
</style>

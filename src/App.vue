<template>
  <div id="app">
    <Header />
    <Main />
    <ServiceSolution />
    <MoveWhitEase />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import ServiceSolution from "./components/ServiceSolution.vue";
import MoveWhitEase from "./components/MoveWithEase.vue";


export default {
  name: "App",
  components: {
    Header,
    Main,
    ServiceSolution,
    MoveWhitEase,
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

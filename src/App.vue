<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <QrScanner />
  </div>
</template>

<script>
import QrScanner from "@/components/QrScanner.vue";
export default {
  name: "App",
  components: {
    QrScanner,
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

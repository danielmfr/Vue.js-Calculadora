<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculadora />
  </div>
</template>

<script>
import Calculadora from "./main/Calculadora.vue";

export default {
  name: "App",
  components: { Calculadora },
};
</script>

<style>
* {
  font-family: "RobotoMono", monospace;
}
body {
  margin: 0;
}
#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100vh;

  color: #fff;
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>

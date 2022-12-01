<template>
  <div id="app">
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./pages/home.vue";

export default {
  components: {
    Calculator,
  },
};
</script>

<style>
* {
  font-family: "robotoMono" monospace;
}

body {
  margin: 0;
  color: white;
  background: rgb(80, 78, 78);
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>

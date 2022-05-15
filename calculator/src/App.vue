<template>
  <div id="app">
    <CalculatorActions/>
  </div>
</template>

<script>
import CalculatorActions from "@/components/CalculatorActions";

export default {
  name: 'App',
  components: {
    CalculatorActions,
  }
}
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

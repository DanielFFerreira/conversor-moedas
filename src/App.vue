<template>
  <div id="app">
    <h1>Conversor de moedas</h1>
    <div class="block">
      <Conversor moeda-a="USD" moeda-b="BRL" />
      <Conversor moeda-a="BRL" moeda-b="USD" />
    </div>

    <div class="block">
      <Conversor moeda-a="CAD" moeda-b="BRL" />
      <Conversor moeda-a="BRL" moeda-b="USD" />
    </div>

    <div class="block">
      <Conversor moeda-a="BRL" moeda-b="BRL" />
      <Conversor moeda-a="HKD" moeda-b="USD" />
    </div>

    <div class="block">
      <Conversor moeda-a="BRL" moeda-b="BRL" />
      <Conversor moeda-a="INR" moeda-b="USD" />
    </div>
  </div>
</template>

<script>
  import Conversor from "./components/Conversor.vue";
  export default {
    name: 'App',
    components: {
      Conversor
    }
  }
</script>

<style>
  #app {
    max-width: 900px;
    margin: 0 auto;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

  .block {
    display: flex;
    justify-content: space-between;
  }
</style>
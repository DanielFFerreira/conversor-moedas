<template>
  <div class="conversor">
    <h2>{{moedaA}} To {{moedaB}}</h2>
    <input type="text" v-bind:placeholder="moedaA">
    <input type="button" value="Converter">
    <h2>{{moedaB_value}}</h2>
  </div>
</template>


<script>
  export default {
    name: "Conversor",
    props: ["moedaA","moedaB"],
    data() {
      return {
        moedaA_value : "",
        moedaB_value : 0,
      }
    }
  }
</script>


<style scoped>

</style>
<template>
  <div class="conversor">
    <h2>{{moedaA}} To {{moedaB}}</h2>
  </div>
</template>


<script>
  export default {
    name: "Conversor",
    props: ["moedaA","moedaB"]
  }
</script>


<style scoped>

</style>
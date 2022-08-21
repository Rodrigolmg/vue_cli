<template>
  <div id="app">
    {{ titulo }}
    <button @click="titulo += '#'">Alterar</button>
  </div>
</template>

<script>
  export default {
    data: function() {
      return {
        titulo: 'Teste usando Vue JS'
      }
    }
  }
</script>

<style>
  #app {
    background-color: burlywood;
    color: red;
  }
</style>
<template>
  <h1 v-if="edad<18">Eres menor de edad</h1>
  <h1 v-else>Eres mayor de edad</h1>
</template>

<script lang="ts" setup>
let edad = 20;
</script>

<style scoped>

</style>

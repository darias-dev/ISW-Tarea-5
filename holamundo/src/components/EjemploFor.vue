<template>
  <ul>
    <li v-for="pais in paises" v-bind:key="pais">{{ pais }}</li>
  </ul>>
</template>

<script lang="ts" setup>
import { Ref, ref } from 'vue'
let paises:Ref<Array<string>> = ref(['España', 'México', 'Argentina', 'Colombia', 'Perú']);
</script>

<style scoped>

</style>

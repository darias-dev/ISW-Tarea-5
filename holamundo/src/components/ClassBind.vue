<template>
  <p v-bind:style="{ backgroundColor :'#ccc', color: c}">El mensaje se envió correctamente</p>
  <button v-on:click="handClick">Cambiar color</button>
</template>

<script lang="ts" setup>
import { ref } from 'vue';
let c = ref('green');
const handClick = () => {
  c.value = c.value === 'green' ? 'red' : 'green';
}
</script>

<style >

</style>

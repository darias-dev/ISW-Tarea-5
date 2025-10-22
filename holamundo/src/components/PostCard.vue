<template>
<div class="post-card">   
  <h3>Hola Mundo</h3>
  <p>Este es un componente de tarjeta de publicación. Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla repudiandae eligendi facere eius inventore alias autem debitis amet, nisi sed optio, repellat iste delectus architecto cum cupiditate doloribus atque facilis?</p>
    <PostButton />
</div>
</template>

<script lang="ts" setup>
    import PostButton from './PostButton.vue';
</script>

<style scoped>
.post-card{
    border: 1px solid #ccc;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 2px 2px 12px rgba(0,0,0,0.1);
    margin: 5px;
}
</style>

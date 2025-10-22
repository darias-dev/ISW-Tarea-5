<template>
  <div class="post-container">
    <PostCard/>
    <PostCard/>
    <PostCard/>
    <PostCard/>
  </div>
</template>

<script lang="ts" setup>
    import PostCard from './PostCard.vue';
</script>
    
<style scoped>
.post-container{
    display: flex;
    flex-wrap: wrap;
    width: 100%;
}
</style>

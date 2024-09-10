<template>
    <div class="emoji-container">
        <component v-for="emoji in emojiToRender" :is="emoji" class="emojies"/>
    </div>
</template>
  
<script setup lang="ts">
import IconCube from '@/styles/icons/IconCube.vue';
import IconCat from '@/styles/icons/IconCat.vue';
import DragonFace from '@/styles/icons/DragonFace.vue';

const emojiToRender = [IconCube, IconCat, DragonFace];
</script>

<style scoped>
.emoji-container {
  height: 100%;
  width: auto;
  padding: 8px;
  gap: 20px;
  background-color: rgba(0, 0, 0, 0.427);
  border: 2px solid black;
  display: flex;
  flex-direction: column;
}
.emojies {
    width:48px;
    height: 48px;
}
</style>

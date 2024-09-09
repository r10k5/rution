<script setup lang="ts">
import AppEmojiContainer from '@/components/AppEmojiContainer.vue';
import AppTiptap from '@/components/AppTiptap.vue';

</script>

<template>
  <div class="main-container">
    <div class="field-container">
      <AppEmojiContainer />
      <AppTiptap />
    </div>
  </div>
</template>

<style scoped>
.field-container {
  width: 80%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.267);
  border: 2px solid black;
  margin-top: 20px;
  display: flex;
}

.main-container {
  width: 100%;
  height: 100%;
  background-color: rgb(43, 43, 102);
  margin: 0px 0px;

  display: flex;
  justify-content: center;
}
</style>
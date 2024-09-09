<template>
  <div class="emoji-container">
    <component :is="emoji.cube" />
  </div>
</template>

<script setup lang="ts">
import { emoji } from './AppEmoji';
</script>

<style scoped>
.emoji-container {
  height: 100%;
  width: auto;
  padding: 8px;
  background-color: rgba(0, 0, 0, 0.427);
  border: 2px solid black;
}
</style>

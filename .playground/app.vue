<script setup lang="ts">
function clack () {
  testLayer()
}
</script>

<template>
  <div>
    <h1>Hello Nuxt Layers!</h1>

    <button class="button" @click="clack()">
      CLICK ME
    </button>
  </div>
</template>

<style>
.button {
  appearance: button;
}
</style>

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
   </div>
</template>

<script setup>
import { defineProps } from 'vue';

defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<style scoped>
h1 {
  margin:40px 0 0;
}

</style>

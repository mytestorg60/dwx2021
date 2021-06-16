<script setup lang="ts">
import { computed, defineProps } from 'vue'
import { handleBackground } from '../layoutHelper'
const props = defineProps({
  image: {
    type: String,
  },
  class: {
    type: String,
  },
  background: {
    default: '',
  },
})
const styleImage = computed(() => handleBackground(props.image))
const styleBackground = computed(() => handleBackground(props.background))
console.log("style "+ styleBackground);

</script>

<template>
  <div class="grid grid-cols-2 w-full h-full" :style="styleBackground">
    <div class="slidev-layout default" :class="props.class">
      <slot />
    </div>
    <div class="w-full w-full" :style="styleImage"></div>
  </div>
</template>

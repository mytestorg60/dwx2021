<script>
export default {
  props: {
    title: {
      type: String,
    },
    social: {
      type: Array,
    },
  },
};
</script>

<template>
  <div
    v-if="title || social"
    class="flex absolute w-full bottom-0 right-2 py-0.5 px-4 text-sm"
  >
    <div class="w-full flex justify-end">
      <a href="https://ionos.com" target="_blank">{{ title }}</a>
      <mdi:minus class="fill-current text-sm" />
      <a href="https://www.ionos.de/impressum" target="_blank">Imprint</a>
    </div>
  </div>
</template>
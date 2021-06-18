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
    class="
      flex
      absolute
      w-full
      bottom-0
      left-0
      py-0.5
      px-4
      text-sm
    "
  >
    <div class="w-1/3 text-left flex justify-start items-center">
      <div><a href="https://ionos.com" target="_blank">{{ title }}</a></div>
    </div>
        <div class="w-1/3 flex justify-center">
          <div >
        <a href="https://www.ionos.de/impressum" target="_blank">Imprint</a>
      </div>
        </div>
    <div class="w-1/3 flex justify-end">
      <div
        v-for="type in social"
        :key="type.type"
        class="flex justify-center items-center ml-4"
      >
        <a
          :href="'https://github.com/' + type.username"
          target="_blank"
          alt="GitHub"
          class="icon-btn !border-none !hover:text-white"
        >
          <LogoIcon :type="type.type" />
        </a>
      </div>
    </div>
  </div>
</template>

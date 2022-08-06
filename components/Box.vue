<!-- eslint-disable vue/multi-word-component-names -->

<template>
  <div>
    <div class="bg-indigo-900 rounded-t p-2 text-white font-semibold border-b border-black">
      <fa :icon="['fas', 'camera']" class="mx-1" /> Samsung S20, f/1.8, 1/1.76" sensor
    </div>
    <img :src="image" class="rounded-b">
  </div>
</template>

<script lang="ts">
export default {
  props: {
    // eslint-disable-next-line vue/require-default-prop
    image: String
  }
}
</script>

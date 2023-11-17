<script setup lang="ts">
  type Props = {
    type?: 'button' | 'submit' | 'reset'
  }
  withDefaults(defineProps<Props>(), {
    type: 'button'
  });
</script>

<template>
  <button
    :type="type"
    v-bind="$attrs"
    class="inline-flex justify-center rounded-lg text-sm font-semibold py-2.5 px-4 bg-slate-900 text-white hover:bg-slate-700 -my-2.5 ml-8"
  >
    <slot />
  </button>
</template>

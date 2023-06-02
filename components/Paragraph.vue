<template>
  <p class="mt-4 text-slate-800 text-justify leading-loose dark:text-slate-200">
    <slot />
  </p>
</template>

<script lang="ts">
export default {
  props: {
    weight: String,
  },
};
</script>

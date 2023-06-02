<template>
  <NuxtLink
    class="text-slate-800 font-semibold border-b border-b-slate-300 hover:border-slate-800 dark:border-b-slate-500 dark:hover:border-b-slate-300 transition-colors dark:text-slate-100"
    :to="to"
  >
    <slot />
  </NuxtLink>
</template>

<script lang="ts">
export default {
  props: {
    to: String,
  },
};
</script>

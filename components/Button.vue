<template>
  <NuxtLink
    
    class="text-slate-800 font-semibold border-b border-b-neutral-500 dark:border-b-neutral-300 dark:text-slate-100"
    :to="to"
  >
    <slot />
  </NuxtLink>
</template>

<script lang="ts">
export default {
  props: {
    to: String
  },
};
</script>

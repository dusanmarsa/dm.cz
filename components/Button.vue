<script lang="ts">
export default {
  props: {
    to: String,
    label: String,
  },
}
</script>

<template>
  <NuxtLink
    class="text-slate-800 font-semibold border-b border-b-neutral-500 dark:border-b-neutral-300 dark:text-slate-100"
    :to="to"
  >
    {{ label }}
  </NuxtLink>
</template>

<template>
  <p class="mt-4 text-slate-700 text-justify leading-loose dark:text-slate-400">
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

<style scoped>
p :deep(b) {
  color: #334155;
}

p :deep(strong) {
  color: #1e293b;
}
.dark p :deep(b) {
  color: #cbd5e1;
}

.dark p :deep(strong) {
  color: #cbd5e1;
}
</style>

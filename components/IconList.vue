<script lang="ts">
export default {
  props: {
    icons: Array<string>,
  },
}
</script>

<template>
  <div class="my-4 flex items-center gap-2">
    <Icon
      v-for="icon in icons"
      :key="icon"
      class="transition-colors duration-150 text-neutral-500 dark:text-neutral-300"
      :name="icon"
      size="24"
    />
  </div>
</template>

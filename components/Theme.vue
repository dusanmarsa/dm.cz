<script lang="ts">
export default {
  methods: {
    setTheme() {
      const theme = this.$colorMode.preference
      this.$colorMode.preference = theme === 'dark' ? 'light' : 'dark'
    },
  },
}
</script>

<template>
  <div class="cursor-pointer p-2 -m-2" @click="setTheme">
    <Icon
      class="transition-colors duration-150 dark:text-white"
      :name="$colorMode.preference === 'light' ? 'carbon:moon' : 'carbon:sun'"
      size="24"
    />
  </div>
</template>

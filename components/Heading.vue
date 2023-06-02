<template>
    <div :class="cssProps">
        <slot />
    </div>
</template>

<script lang="ts">
export default {
  props: {
    customClass: String,
  },
  computed: {
    cssProps() {
        return `text-slate-900 mt-10 mb-2 tracking-wider dark:text-slate-100 ${this.customClass}`
    }
  }
};
</script>

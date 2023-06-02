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
        return `text-4xl text-slate-900 tracking-wider dark:text-slate-100 ${this.customClass}`
    }
  }
};
</script>

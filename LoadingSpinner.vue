<template>
  <div class="c-loading-spinner">
    <svg class="c-loading-spinner__svg" viewBox="0 0 66 66" xmlns="http://www.w3.org/2000/svg">
      <circle
        class="c-loading-spinner__circle"
        fill="none"
        stroke-width="6"
        stroke-linecap="round"
        cx="33"
        cy="33"
        r="30"
      ></circle>
    </svg>
    <div class="c-loading-spinner__text">{{ loadingText }}</div>
  </div>
</template>

<script>
export default {
  props: {
    loadingText: {
      type: String,
      default: 'Loading',
    },
  },
};
</script>

<style lang="scss" scoped>
@import './LoadingSpinner';
</style>

<template>
  <div class="wrapper">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'LayoutWrapper',
}
</script>

<style scoped>
.warpper {
  padding-top: 80px;
  @media (min-width: 768px) {
    padding-top: 0;
  }
}
</style>

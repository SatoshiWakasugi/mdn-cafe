<template>
  <div>
    <h2 class="font-sans text-lg text-gray-800 text-center text-3xl mb-10">
      <slot />
    </h2>
   </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'BaseHeading',
})
</script>

<style scoped>
h1 {
  font-size: 30px;
  font-weight: bold;
}
</style>

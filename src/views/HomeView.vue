<template>
  <div class="game">
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue'

export default defineComponent({
  setup () {
    const width = ref(300)

    return {
      width
    }
  }
})
</script>

<style lang="scss">
  .game {
    width: 100vw;
    height: 100vh;
  }
</style>

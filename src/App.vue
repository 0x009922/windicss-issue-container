<template>
  <div class="container border-2 border-blue-600 mt-20 text-center p-4">
    Hello, resize window horizontally and you will see,
    that there no any horizontal padding <b>outside of container</b>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
})
</script>

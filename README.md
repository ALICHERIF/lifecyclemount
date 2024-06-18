# lifecyclemount
lifecyclemount
<script setup>
import { ref,onMounted } from 'vue'

const pElementRef = ref(null)
onMounted(() => {
  // component is now mounted.
  pElementRef.value.textContent="hi"
})
</script>

<template>
  <p ref="pElementRef">Hello</p>
</template>

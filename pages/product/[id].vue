<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    Page: product/{{ route.params.id }}
  </div>
</template>

<style scoped></style>

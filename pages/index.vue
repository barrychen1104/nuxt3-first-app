<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <div>
   <h1>Page: 首頁</h1>
   <p>目前路由的路徑 - route.fullPath為:{{ route.fullPath }} </p>
  </div>
</template>

<style scoped></style>

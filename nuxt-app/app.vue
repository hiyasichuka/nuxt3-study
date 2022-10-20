<template>
  <div>
    <p>{{ sampleHtml }}</p>
  </div>
</template>

<script setup lang="ts">
const { data: sampleHtml } = useFetch("https://example.com/");
</script>


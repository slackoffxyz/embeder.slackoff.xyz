<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Embed Poster',
  meta: [
    { name: 'description', content: 'Create and post Discord embeds via webhooks' },
  ],
})
</script>

<template>
  <router-view />
</template>

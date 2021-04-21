<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Podcastr',
  meta: [
    { name: 'description', content: '' },
  ],
})
</script>

<template>
  <router-view />
</template>

<template>
  <NuxtPage />
</template>

<script setup lang="ts">
  const appConfig = useAppConfig()

  useHead({
    title: appConfig.title
  })
</script>
<template>
  <NuxtPage />
</template>

<script setup lang="ts">
  const appConfig = useAppConfig()

  useHead({
    title: appConfig.title,
    meta: [
      { name: "description", content: appConfig.description }
    ]
  })
</script>
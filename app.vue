<template>
  <NuxtPage />
</template>

<script setup lang="ts">
  const appConfig = useAppConfig()

  useHead({
    title: appConfig.title,
    meta: [
      { name: "description", content: "portfolio and profile Abdul Qirom"}
    ]
  })
</script>
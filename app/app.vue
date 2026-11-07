<template>
  <UApp>
    <NuxtRouteAnnouncer />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </UApp>
</template>

<script setup lang="ts">
useHead({ titleTemplate: (title?: string) => (title ? `${title} - Вишлист` : 'Вишлист') })
</script>

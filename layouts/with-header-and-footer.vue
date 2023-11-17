<script setup lang="ts">
const { myLayer } = useAppConfig()
</script>

<template>
  <div>
    <AppHeader :title="myLayer.name" />
    <main class="h-full max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
      <slot />
    </main>
    <AppFooter />
  </div>
</template>

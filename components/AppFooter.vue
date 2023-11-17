<script setup lang="ts">
const { myLayer } = useAppConfig()
</script>

<template>
  <footer class="w-full bg-primary-100">
    <nav class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8 flex justify-between items-center">
      <div class="flex items-center">
        <a
          href="#"
          class="text-primary-500 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
        >Home</a>
        <a
          href="#"
          class="text-primary-500 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
        >About</a>
        <a
          href="#"
          class="text-primary-500 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
        >Contact</a>
      </div>
      <div class="text-primary-500 text-sm">
        &copy; 2023 {{ myLayer.name }}
      </div>
    </nav>
  </footer>
</template>

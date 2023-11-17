
<script
  setup
  lang="ts"
>
  defineProps<{
  title: string
  }>();
</script>

<template>
  <header class="w-full bg-primary-600">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center py-4">
      <h1 class="text-white text-2xl font-bold">
        {{ title }}
      </h1>
      <nav>
        <ul class="flex space-x-4 text-white">
          <li>
            <a href="#">Link 1</a>
          </li>
          <li>
            <a href="#">Link 2</a>
          </li>
          <li>
            <a href="#">Link 3</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

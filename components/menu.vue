<template>
  <nav class="font-mono">
    <ul class="flex flex-col md:flex-row md:space-x-4">
      <li>
        <NuxtLink
          to="/"
          class="p1 hover:bg-gray-200 dark:hover:bg-gray-800 text-2xl md:text-base"
          >Main</NuxtLink
        >
      </li>
      <li>
        <NuxtLink
          to="/about"
          class="p1 hover:bg-gray-200 dark:hover:bg-gray-800 text-2xl md:text-base"
          >About</NuxtLink
        >
      </li>
      <li>
        <NuxtLink
          to="/projects"
          class="p1 hover:bg-gray-200 dark:hover:bg-gray-800 text-2xl md:text-base"
          >Projects</NuxtLink
        >
      </li>
      <li>
        <NuxtLink
          to="/blog"
          class="p1 hover:bg-gray-200 dark:hover:bg-gray-800 text-2xl md:text-base"
          >Blog</NuxtLink
        >
      </li>
    </ul>
  </nav>
</template>

<script setup></script>

<style scoped></style>

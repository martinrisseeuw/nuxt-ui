<template>
  <nav class="p-4 border-b border-gray-100 dark:border-gray-800 bg-gray-50 text-black dark:bg-gray-900 dark:text-white">
    <button @click="$colorMode.preference = 'dark'">dark</button>
    <button @click="$colorMode.preference = 'light'">light</button>
  </nav>
</template>
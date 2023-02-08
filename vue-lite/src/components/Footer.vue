<script setup lang="ts">
</script>

<template>
  <nav class="icon-color mt-6 flex items-center justify-center gap-4 text-2xl opacity-75">
    <RouterLink class="hover:text-teal-600" to="/" title="Home">
      <div class="i-carbon-campsite" />
    </RouterLink>

    <button class="hover:text-teal-600" title="Toggle dark mode" @click="toggleDark()">
      <div class="i-carbon-sun dark:i-carbon-moon" />
    </button>

    <RouterLink class="hover:text-teal-600" to="/about" title="About">
      <div class="i-carbon-dicom-overlay" />
    </RouterLink>

    <a rel="noreferrer" href="https://github.com/zguolee/starter" target="_blank" title="GitHub">
      <div class="i-carbon-logo-github" />
    </a>
  </nav>
</template>

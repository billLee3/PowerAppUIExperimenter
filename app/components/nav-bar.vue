<script setup lang="ts"></script>

<template>
  <UHeader
    title="Nuxt UI 2"
    class="bg-purple-900 border border-solid border-white dark:text-white"
    to="/"
  >
    <template></template>

    <!-- <UNavigationMenu :items="items" /> -->

    <template #right>
      <UButton color="neutral" variant="outline" to="/about">About</UButton>
      <UTooltip text="Open on GitHub" :kbds="['meta', 'G']">
        <UButton
          color="neutral"
          variant="ghost"
          to="https://github.com/nuxt/ui"
          target="_blank"
          icon="i-simple-icons-github"
          aria-label="GitHub"
        />
      </UTooltip>
    </template>
  </UHeader>
</template>

<style scoped>
.custom {
  background-color: green;
}
</style>

<script setup lang="ts">
import type { NavigationMenuItem } from "@nuxt/ui";

const items: NavigationMenuItem[] = [
  {
    label: "Power Apps Themes",
    to: "https://go.nuxt.com/figma-ui",
    target: "_blank",
  },
  {
    label: "Releases",
    to: "https://github.com/nuxt/ui/releases",
    target: "_blank",
  },
];
</script>

<template>
  <UFooter
    class="w-screen py-0 border-gray-600 border-solid border bg-gray-700"
  >
    <!-- <template #left> </template> -->
    <UNavigationMenu :items="items" variant="pill" external-icon="false" />
    <template #right>
      <p class="text-muted text-sm">
        Copyright © {{ new Date().getFullYear() }}
      </p>
    </template>
  </UFooter>
</template>

<script setup lang="ts">
import NavBar from "~/components/nav-bar.vue";
</script>

<template>
  <div>
    <NavBar />
    <UMain class="flex justify-center items-center">
      <slot />
    </UMain>
    <FooterComponent />
  </div>
</template>

<style scoped></style>

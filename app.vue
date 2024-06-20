<template>
  <NuxtPage />
</template>
<script setup lang="ts">
import { SafeArea } from "@capacitor-community/safe-area";

SafeArea.enable({
  config: {
    customColorsForSystemBars: true,
    statusBarColor: "#00000000", // transparent
    statusBarContent: "light",
    navigationBarColor: "#00000000", // transparent
    navigationBarContent: "light",
  },
});
//npx
//npx nuxi@latest init <project-name>
//pnpm
//pnpm dlx nuxi@latest init <project-name>
//npx
// npx nuxi@latest module add ionic
// pnpm dlx nuxi@latest module add ionic
// cap sync
// npx cap sync
//  pnpm dlx cap sync
</script>

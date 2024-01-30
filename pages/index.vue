<script setup lang="ts">
import App from "~/pages/app.vue";

const appConfig = useAppConfig()
</script>
<template>
  <div>
    <app></app>
    <h1>Welcome to the homepage</h1>
    <AppAlert>
      This is an auto-imported component
    </AppAlert>
  </div>
</template>
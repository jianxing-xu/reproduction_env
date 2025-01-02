<script setup lang="ts">

const config = useRuntimeConfig();

console.log(config.public.apiBase)
</script>
<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>

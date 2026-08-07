<script setup lang="ts">
import '../../assets/styles/components/hello-world.css'

defineProps<{
  message: string
}>()
</script>

<template>
  <section class="hello-card">
    <h1 class="hello-card__title">{{ message }}</h1>
    <p class="hello-card__subtitle">Vue 3 + TypeScript ist eingerichtet.</p>
  </section>
</template>

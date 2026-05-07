<script setup lang="ts">
import { useNav } from '@slidev/client'

defineProps<{
  section?: string
}>()

const { currentPage } = useNav()

function pad(n: number) {
  return String(n).padStart(2, '0')
}
</script>

<template>
  <div class="text-xs tracking-[0.3em] text-[#F96167] font-mono">
    <template v-if="section">{{ pad(currentPage) }} · {{ section }}</template>
    <slot v-else />
  </div>
</template>

<script setup lang="ts">
import { computed } from 'vue'
import { useNav } from '@slidev/client'

const props = defineProps<{
  light?: boolean
}>()

const { currentPage, total } = useNav()

const colorClass = computed(() => (props.light ? 'text-[#6B6E80]' : 'text-[#AAB1C7]'))
</script>

<template>
  <div
    class="absolute bottom-4 left-16 right-16 flex justify-end text-xs font-mono"
    :class="colorClass"
  >
    <span>{{ currentPage }} / {{ total }}</span>
  </div>
</template>

<script setup lang="ts">
import { onMounted, ref, watch } from 'vue'

const props = withDefaults(defineProps<{
  to: number
  duration?: number
  prefix?: string
  suffix?: string
  start?: boolean
}>(), {
  duration: 1500,
  prefix: '',
  suffix: '',
  start: true,
})

const current = ref(0)
let started = false

function begin() {
  if (started) return
  started = true
  const startTime = performance.now()
  function step(now: number) {
    const t = Math.min((now - startTime) / props.duration, 1)
    const eased = 1 - Math.pow(1 - t, 3)
    current.value = Math.floor(eased * props.to)
    if (t < 1) requestAnimationFrame(step)
    else current.value = props.to
  }
  requestAnimationFrame(step)
}

onMounted(() => {
  if (props.start) begin()
})

watch(() => props.start, (v) => {
  if (v) begin()
})
</script>

<template>
  <span>{{ prefix }}{{ current.toLocaleString('ko-KR') }}{{ suffix }}</span>
</template>

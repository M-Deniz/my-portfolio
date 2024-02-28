<script setup lang="ts">
defineProps<{
  icon: string
  alignIconTop?: boolean
  renderImage?: boolean
}>()
</script>

<template>
  <section class="border-color-400" :class="[alignIconTop ? 'flex-col-reverse' : 'flex-col']" block flex items-center justify-center gap-2 border rounded-lg>
    <span>
      <slot>
        VIconButton
      </slot>
    </span>

    <div v-if="!renderImage" :class="icon" text-3xl />

    <slot v-else name="icon">
      Image
    </slot>
  </section>
</template>

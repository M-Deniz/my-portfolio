<script setup lang="ts">
defineProps<{
  icon?: string
  iconSize?: string
  alignIconLeft?: boolean
  renderImage?: boolean
}>()
</script>

<template>
  <button border class="border-color-400 hover-animation" rounded-lg>
    <div flex items-center justify-center gap-2 px-2 py-1 :class="[alignIconLeft ? 'flex-row-reverse' : 'flex-row']">
      <span>
        <slot>
          VIconButton
        </slot>
      </span>

      <div v-if="!renderImage" :class="`${icon} ${iconSize ?? 'text-base'}`" />

      <slot v-else name="icon">
        Image
      </slot>
    </div>
  </button>
</template>

<!--
  Usage:
```md
---
layout: physical-spiritual
---
::left::
This shows on the left

::physical:: 
This shows left center in gray

::spiritual::
This shows right center in blue

::right::
This shows on the right
```
-->

<script setup lang="ts">
const props = defineProps({
  class: {
    type: String,
  },
})
</script>

<template>
<div class="grid grid-cols-4 gap-0 w-full h-full">
    <div :class="props.class"><slot name="left" /></div>
    <div :class="props.class"><slot name="physical" /></div>
    <div :class="props.class"><slot name="spiritual" /></div>
    <div :class="props.class"><slot name="right" /></div>
  </div>
</template>
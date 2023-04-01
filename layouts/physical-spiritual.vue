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

<script setup lang='ts'>
const props = defineProps({
  class: {
    type: String,
  },
})
</script>

<template>
  <div class='grid grid-cols-4 gap-0 font-bold p-1'>
    <div class='text-2xl' :class='props.class'>
      <slot name='left' />
    </div>

    <div class='bg-sky-400
              text-blue-800
              text-3xl
              border-r-1
              border-black 
              [&>*:first-child]:text-5xl
              [&>*:first-child]:border-b-2
              [&>*:first-child]:border-black
              [&>*:first-child]:font-bold'
              :class='props.class'>
      <slot name='spiritual' />
    </div>

    <div class='bg-gray-400
              text-zinc-800
              text-3xl
              border-l-1
              border-black
              [&>*:first-child]:text-5xl
              [&>*:first-child]:border-b-2
              [&>*:first-child]:border-black
              [&>*:first-child]:font-bold'
              :class='props.class'>
      <slot name='physical' />
    </div>

    <div class='text-2xl' :class='props.class'>
      <slot name='right' />
    </div>
</div></template>
<template>
  <div class="w-full flex flex-col justify-between items-center shadow-2xl">
    <div class="w-full">
      <slot name="top"></slot>
    </div>
    <div class="w-full h-full">
      <slot name="image"></slot>
    </div>
    <div class="w-full">
      <slot name="bottom"></slot>
      <slot></slot>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
</style>
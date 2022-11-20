<template>
  <div
    class="h-28 w-20 absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] rounded-2xl"
    :class="styles"
  ></div>
</template>
<script setup>
  const props = defineProps({
    styles: String,
  });
</script>

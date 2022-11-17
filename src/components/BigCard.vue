<template>
  <div
    class="h-60 w-44 absolute top-[50%] left-[50%] -translate-x-[50%] -translate-y-[50%] rounded-2xl"
    :class="styles"
  ></div>
</template>
<script setup>
  const props = defineProps({
    styles: String,
  });
</script>

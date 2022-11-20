<template>
  <div
    class="h-60 w-44 absolute rounded-2xl bg-cover bg-no-repeat"
    :class="styles"
  ></div>
</template>
<script setup>
  const props = defineProps({
    styles: String,
  });
</script>

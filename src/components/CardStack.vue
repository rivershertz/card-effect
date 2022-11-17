<template>
  <div class="w-[40vw] h-[50%] relative border">
    <BigCard styles="rotate-3 bg-violet-300" />
    <SmallCard />
    <BigCard styles="-rotate-3 bg-violet-400" />
    <SmallCard />
    <BigCard styles="-rotate-6 bg-violet-600" />
    <SmallCard />
    <BigCard styles="rotate-7 bg-violet-800" />
    <SmallCard />
  </div>
</template>
<script setup>
  import SmallCard from './SmallCard.vue';
  import BigCard from './BigCard.vue';
</script>

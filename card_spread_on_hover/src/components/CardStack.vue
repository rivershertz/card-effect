<template>
  <div class="h-60 w-44 relative wrapper">
    <SmallCard styles="bg-amber-200 card" />
    <BigCard
      styles="rotate-3 bg-[url(https://images.unsplash.com/photo-1500817487388-039e623edc21?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=989&q=80)] card"
    />
    <SmallCard styles="bg-amber-200 card" />
    <BigCard
      styles="-rotate-3 bg-[url(https://images.unsplash.com/photo-1536152470836-b943b246224c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1038&q=80)] card"
    />
    <SmallCard styles="bg-amber-200 card" />
    <BigCard
      styles="-rotate-6 bg-[url(https://images.unsplash.com/photo-1485201543483-f06c8d2a8fb4?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OXx8bGFuZHNjYXBlfGVufDB8MXwwfHw%3D&auto=format&fit=crop&w=800&q=60)] card"
    />
    <SmallCard styles="bg-amber-200 card" />
    <BigCard
      styles="rotate-7 bg-[url(https://images.unsplash.com/photo-1600240644455-3edc55c375fe?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTF8fGxhbmRzY2FwZXxlbnwwfDF8MHx8&auto=format&fit=crop&w=800&q=60)] card"
    />
  </div>
</template>
<script setup>
  import SmallCard from './SmallCard.vue';
  import BigCard from './BigCard.vue';
</script>

<style scoped>
  .wrapper:hover div:nth-child(2) {
    transform: translate(-60%, 3%) rotate(-5deg);
  }
  .wrapper:hover div:nth-child(4) {
    transform: translate(-20%, 1%) rotate(-2deg);
  }
  .wrapper:hover div:nth-child(6) {
    transform: translate(20%, 1%) rotate(2deg);
  }
  .wrapper:hover div:nth-child(8) {
    transform: translate(60%, 3%) rotate(5deg);
  }
  .wrapper:hover div:nth-child(1) {
    transform: translate(-200%, -200%) rotate(5deg);
  }
  .wrapper:hover div:nth-child(3) {
    transform: translate(100%, -200%) rotate(-5deg);
  }
  .wrapper:hover div:nth-child(5) {
    transform: translate(-200%, 100%) rotate(-5deg);
  }
  .wrapper:hover div:nth-child(7) {
    transform: translate(100%, 100%) rotate(5deg);
  }

  .card {
    transition: transform 600ms cubic-bezier(0, 0.66, 0.26, 0.91);
    box-shadow: -5px 0 10px rgb(32, 32, 32);
  }
</style>

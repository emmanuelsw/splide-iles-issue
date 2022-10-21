<script setup lang="ts">
import { Splide, SplideSlide } from '@splidejs/vue-splide';
</script>

<template>
  <Splide :options="{ rewind: true }" aria-label="My Favorite Images">
    <SplideSlide>
      <img src="https://images.unsplash.com/photo-1603919768617-34ed57b89136?auto=format&fit=crop&w=1280&q=80" alt="Sample 1">
    </SplideSlide>
    <SplideSlide>
      <img src="https://images.unsplash.com/photo-1659114245023-26543e9a75c8?auto=format&fit=crop&w=1280&q=80" alt="Sample 2">
    </SplideSlide>
  </Splide>
</template>
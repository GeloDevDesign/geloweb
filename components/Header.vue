<script setup>
const props = defineProps({
  headerName: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <h1 class="animate-fade-up animate-once animate-delay-100  lg:text-7xl md:text-4xl text-3xl font-semibold lg:max-w-5/6 md:w-full w-full lg:leading-24 md:leading-16 leading-12">  
    {{ headerName }}
  </h1>
</template>

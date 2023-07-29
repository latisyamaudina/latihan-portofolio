<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://static.vecteezy.com/system/resources/previews/010/925/820/original/colorful-welcome-design-template-free-vector.jpg',
    'alt': 'Picture 1',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>

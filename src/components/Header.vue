<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://wallpaperaccess.com/full/399625.jpg',
    'alt': 'Picture 3',
  },
  {
    'src': 'https://wallpapercave.com/wp/wp2576999.jpg',
    'alt': 'Picture 4',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>




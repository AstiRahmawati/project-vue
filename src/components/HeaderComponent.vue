<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://shila.co.id/wp-content/uploads/2023/06/portico_landscape.jpg.webp',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://asset-2.tstatic.net/tribunnews/foto/bank/images/serpong-facade-b_20180515_110222.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://1.bp.blogspot.com/-UxcLU1qRE88/YWUpAp6CGvI/AAAAAAAAMdY/tkGn76RwH44hiYpq61oOkIKdtcUKxbMtACLcBGAsYHQ/s543/Rumah-Panggung-Minimalis-Cantik.jpg',
    'alt': 'Picture 3',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>
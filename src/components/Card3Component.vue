<script setup>
import { TheCard } from 'flowbite-vue'
import { Rating } from 'flowbite-vue'
</script>
<template>
    <br>
    <br>
    <br>
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"><center>Mewah</center></h5>
    <div class="flex flex-row">
  <div class="basis-1/2 mx-10">
    <br>
    <the-card variant="image" img-src="https://arsitagx-master-article.s3.ap-southeast-1.amazonaws.com/article-photo/983/rumah-minimalis-3-lantai-1.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Fasad Clean Look Modern</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        3 lantai ini benar-benar membuat takjub. Fasad terlihat clean look dan sekaligus modern. Tampak berbeda dibanding hunian-hunian di sekitarnya. Fasad clean look modern ini tak lain dihasilkan dari bentuk-bentuk dasar geometris yang diaplikasikan pada fasad rumah tiga lantai, pengulangan struktur, dan peniadaan ornamen-ornamen yang rumit.
    </p>
    <br>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="1023 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
      </template>
    </Rating>
  </the-card>
  </div>
  <div class="basis-1/2">
    <br>
    <the-card variant="image" img-src="https://arsitagx-master-article.s3.ap-southeast-1.amazonaws.com/article-photo/1044/desain-interior-mewah-cover.jpeg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Desain Interior Mewah dan Berkelas</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Desain interior mewah dapat dihadirkan dengan berbagai cara. Salah satu kuncinya adalah keseimbangan semua komponen sehingga kesan mewah tersebut terlihat elegan, berkelas, dan tidak mengabaikan aspek kenyamanan. Sebuah hunian 3 lantai di daerah Jakarta menunjukkan cara menghadirkan semua aspek tersebut di dalamnya, tanpa memberikan kesan dingin atau berlebihan.
    </p>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="958 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
      </template>
    </Rating>
  </the-card>
  </div>
  <div class="basis-1/2">
    <br>
    <the-card variant="image" img-src="https://events.rumah123.com/news-content/img/2020/10/09005153/3-floor-house-9-1024x683.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Rumah kaca</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      Desain interior mewah dapat dihadirkan dengan berbagai cara. Salah satu kuncinya adalah keseimbangan semua komponen sehingga kesan mewah tersebut terlihat elegan, berkelas, dan tidak mengabaikan aspek kenyamanan. Sebuah hunian 3 lantai di daerah Jakarta menunjukkan cara menghadirkan semua aspek tersebut di dalamnya, tanpa memberikan kesan dingin atau berlebihan.
  </p>
  <br>
  <br>
  <Rating
      :rating="1"
      :scale="1"
      review-text="997 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
      </template>
    </Rating>
    </the-card>
  </div>
</div>
</template>

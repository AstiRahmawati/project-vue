<script setup>
import { TheCard } from 'flowbite-vue'
import { Rating } from 'flowbite-vue'
</script>
<template>
    <br>
    <br>
    <br>
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"><center>Sederhana</center></h5>
    <div class="flex flex-row">
  <div class="basis-1/2 mx-10">
    <br>
    <the-card variant="image" img-src=https://events.rumah123.com/news-content/img/2021/07/01090637/Gambar-Desain-Rumah-Minimalis-1-Lantai-pinterest-6.jpg img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">1 Lantai Sederhana Nan Elegan</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Desain rumah 1 lantai mewah ini memiliki kekuatan pada tampilannya yang sederhana, simpel tetapi tetap menarik.
    </p>
    <br>
    <br>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="73 reviews"
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
    <the-card variant="image" img-src="https://events.rumah123.com/news-content/img/2021/07/01090638/Gambar-Desain-Rumah-Minimalis-1-Lantai-pinterest-7.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Rumah 1 Lantai dengan Pagar Minimalis</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Pagar rumah minimalis menjadi elemen penting dalam sebuah hunian modern. Model rumah dengan pagar tembok minimalis ini akan membuat hunian aman sekaligus estetik.
    </p>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="73 reviews"
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
    <the-card variant="image" img-src="https://events.rumah123.com/news-content/img/2021/07/01090644/Gambar-Desain-Rumah-Minimalis-1-Lantai-pinterest-10.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Rumah 1 Lantai Kolonial Modern</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Model rumah minimalis ini terinspirasi dari gaya arsitektur kolonial modern, bisa dilihat dari dominasi warna cat putih.
    </p>
    <br>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="73 reviews"
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

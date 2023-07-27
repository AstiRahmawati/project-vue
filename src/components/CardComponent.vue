<script setup>
import { TheCard } from 'flowbite-vue'
import { Rating } from 'flowbite-vue'
</script>
<template>
    <br>
    <br>
    <br>
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"><center>Minimalis</center></h5>
    <div class="flex flex-row">
  <div class="basis-1/2 mx-10">
    <br>
    <the-card variant="image" img-src="https://img.iproperty.com.my/angel/750x1000-fit/wp-content/uploads/sites/5/2022/09/Alt-Text-5.-Rumah-Minimalis-2-Lantai-Type-36-Sederhana.png" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">2 Lantai Type 36 Sederhana</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Desain rumah minimalis 2 lantai type 36 selanjutnya adalah bagi mereka yang menyukai desain sederhana. Rumah tidak memiliki banyak detail dan ornamen, dibangun sesederhana mungkin. Seperti bagian garasi di dalam rumah yang bersebelahan langsung dengan ruang tamu, serta teras kecil pada bagian depan rumah.
    </p>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="750 reviews"
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
    <the-card variant="image" img-src="https://img.iproperty.com.my/angel/750x1000-fit/wp-content/uploads/sites/5/2022/09/Alt-Text-6.-Rumah-Minimalis-2-Lantai-Type-36-Hook.png" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">2 Lantai Type 36 Hook</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Bagi mereka yang mempunyai rumah type 36 di hook atau pinggir/pojok, desain rumah minimalis 2 lantai ini sangat cocok. Biasanya, rumah di hook memiliki luas tanah lebih, hal ini bisa dimanfaatkan untuk membangun bangunan yang sedikit lebih luas.
    </p>
    <br>
    <br>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="549 reviews"
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
    <the-card variant="image" img-src="https://img.iproperty.com.my/angel/750x1000-fit/wp-content/uploads/sites/5/2022/09/Alt-Text-7.-Rumah-Minimalis-2-Lantai-Type-36-Balkon.png" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">2 Lantai Type 36 Balkon</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Memiliki rumah 2 lantai tanpa balkon rasanya kurang lengkap, ini bisa diatasi melalui rumah minimalis 2 lantai type 36 balkon. Rumah dibangun secara memanjang dengan bagian depan rumah yang cukup luas untuk menyimpan kendaraan bermotor dan taman.
    </p>
    <br>
    <br>
    <Rating
      :rating="1"
      :scale="1"
      review-text="975 reviews"
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

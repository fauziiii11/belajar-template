<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
    <hr>
    <br>
    <div><h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">POPULARITY SHOES</h5></div>
    <br>
  <div class="grid grid-cols-3 gap-4">
  <div><the-card href="#" variant="vertical" img-src="https://www.adidas.co.id/media/catalog/product/cache/ffbe5d912e2813a20bb27461a01c1e7c/i/f/if3402_2_footwear_photography_side_lateral_view_grey.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Casual Adidas Shoes</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        IDR 1.700.000,00
    </p>
  </the-card></div>
  <!-- ... -->
  <div><the-card href="#" variant="vertical" img-src="https://www.adidas.co.id/media/catalog/product/cache/ffbe5d912e2813a20bb27461a01c1e7c/i/e/ie1989_2_footwear_photography_side_lateral_view_grey.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Sport Adidas Shoes</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">IDR 1.100.000,00
    </p>
  </the-card></div>
  <div>
    <the-card href="#" variant="vertical" img-src="https://www.adidas.co.id/media/catalog/product/cache/3bec5fdb79d91223b1a151be2b21ce8d/i/e/ie1588_1_footwear_photography_side20lateral20center20view_grey.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">FootBall Adidas Shoes</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">IDR 2.000.000,00
    </p>
  </the-card>
  </div>
  
  </div>
</template>



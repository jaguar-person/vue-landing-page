<script setup>
import Table from "./Table.vue";
</script>
<template>
  <div
    class="bg-[url('./assets/images/block3.png')] bg-left flex items-center justify-center flex-col gap-4 pt-20 relative"
  >
    <img
      src="../assets/images/block3-img1.png"
      class="absolute bottom-96 right-0 z-10 mt-40"
    />
    <img
      src="../assets/images/block3-img3.png"
      class="absolute top-96 right-0 z-10 mt-40"
    />
    <h2 class="font-bold text-[3rem] w-2/3 text-center px-12">
      Buy and sell with the lowest fees in the industry
    </h2>
    <p class="text-[#898CA9] w-1/2 text-center px-12">
      Buy and sell 150+ cryptocurrencies with 20+ fiat currencies using bank
      transfers or your credit/debit card.
    </p>
    <button class="text-[#B982FF]">Learn more →</button>
    <div
      class="bg-[#1A1B23] w-5/6 rounded-xl z-10 text-lg font-semibold center px-6"
    >
      <Table />
    </div>
    <div class="flex items-center justify-start mt-32 px-32">
      <div class="flex flex-col items-start justify-center gap-5">
        <h2 class="font-bold text-[3rem]">
          Take your first step into safe, secure crypto investing
        </h2>
        <p class="text-[#898CA9] text-sm">
          Separated they live in Bookmarks right at the coast of the famous
          Semantics, large language ocean Separated they live in Bookmarks right
          at the coast.
        </p>
        <button
          class="py-3 px-6 rounded-lg bg-gradient-225 from-[#18C8FF] to-[#933FFE]"
        >
          Get Started
        </button>
      </div>
      <img src="../assets/images/block3-img2.png" class="z-10" />
    </div>
  </div>
</template>

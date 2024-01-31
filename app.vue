<script setup>
import Navbar from "@/components/Navbar.vue";
import Fixed_Navbar from "@/components/Fixed_Navbar.vue";

import imgUrl from "./public/imgUrl.avif";
</script>

<template>
  <div class="app">
    <Navbar />
    <Fixed_Navbar />
    <div class="bg-cover bg-center">
      <img :src="imgUrl" />
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Encode+Sans:wght@400;700&display=swap");

.app {
  font-family: "Encode Sans", sans-serif;
}
</style>

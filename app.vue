<script setup>
import Navbar from "@/components/Navbar.vue";
import Fixed_Navbar from "@/components/Fixed_Navbar.vue";
import Search from "@/components/Search.vue";
import imgUrl from "@/assets/imgUrl.png";
</script>

<template>
  <div class="app">
    <Navbar />
    <Fixed_Navbar />
    <Search />
    <div class="image_bg">
      <img :src="imgUrl" alt="mountains" />
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Encode+Sans:wght@400;700&display=swap");

.app {
  font-family: "Encode Sans", sans-serif;
}

img {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  z-index: -1;
}
</style>

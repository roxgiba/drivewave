<script setup>
import Navbar from "@/components/Navbar.vue";
import Fixed_Navbar from "@/components/Fixed_Navbar.vue";
import Search from "@/components/Search.vue";
// import imgUrl from "@/assets/imgUrl.png";
</script>

<template>
  <div class="app">
    <nav>
      <Navbar />
      <Fixed_Navbar />
    </nav>
    <main>
      <Search />
    </main>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Encode+Sans:wght@400;700&display=swap");

* {
  box-sizing: content-box;
}

.app {
  font-family: "Encode Sans", sans-serif;
}
</style>

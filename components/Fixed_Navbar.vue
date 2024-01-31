<script setup>
import { Menu, MenuButton, MenuItems, MenuItem } from "@headlessui/vue";
</script>

<template>
  <section class="menu">
    <div class="dropdown">
      <div>Locations</div>
      <div>Blog</div>
      <div>Rates</div>
    </div>
    <div class="language">UK|EUR</div>
  </section>
</template>

<style>
.menu {
  display: flex;
  justify-content: space-between;
  width: 70%;
  margin: 20px auto;
}

.dropdown {
  display: flex;
  justify-content: space-evenly;
  width: 50%;
}

.language {
  display: flex;
  justify-content: right;
  width: 30%;
  margin: auto;
}
</style>

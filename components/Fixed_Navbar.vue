<script setup>
import { Menu, MenuButton, MenuItems, MenuItem } from "@headlessui/vue";
</script>

<template>
 <!-- <section class="menu">
    <div class="dropdown">
      <div>Locations</div>
      <div>Blog</div>
      <div>Rates</div>
    </div>
    <div class="language">UK|EUR</div>
  </section> -->

  <div class="menu">
    <b-dropdown class="dropdown m-md-2" id="dropdown-1" text="Motorhome Hire">
    <b-dropdown-item href="#">Campervan Hire</b-dropdown-item>
    <b-dropdown-item href="#">Motorhome Hire</b-dropdown-item>
    <b-dropdown-item href="#"><a href="">All campervans & motorhomes</a></b-dropdown-item>
  </b-dropdown>
    
  <b-dropdown class="dropdown m-md-2" id="dropdown-1" text="Locations">
    <b-dropdown-item href="#">List of countries</b-dropdown-item>
  </b-dropdown>

    <b-dropdown class="dropdown m-md-2" id="dropdown-1" text="Blog">
    <b-dropdown-item href="#">Locations</b-dropdown-item>
    <b-dropdown-item href="#">Blog</b-dropdown-item>
    <b-dropdown-item href="#">Rates</b-dropdown-item>
  </b-dropdown>

    <b-dropdown class="dropdown m-md-2" id="dropdown-1" text="Rates">
  </b-dropdown>
</div>
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

<template>
  <nav class="bg-blue-500 p-4" style="position: sticky; top: 0">
    <div class="container mx-auto flex justify-between items-center">
      <a href="#" class="text-white text-2xl font-semibold">Beethor</a>
      <ul class="flex space-x-4">
        <li>
          <nuxt-link to="/" class="text-white">ໜ້າຫຼັກ</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about" class="text-white">ກ່ຽວກັບ</nuxt-link>
        </li>
        <li>
          <nuxt-link class="text-white">ການບໍລິການ</nuxt-link>
        </li>
        <li>
          <nuxt-link class="text-white">ຕິດຕໍ່ພວກເຮົາ</nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script setup lang="ts"></script>

<style scoped></style>

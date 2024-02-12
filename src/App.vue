<script setup lang="ts"></script>

<template>
  <header>
    <div class="bg-[#180176] text-white text-xl flex justify-center py-3">
      <RouterLink :to="{ name: 'home' }" class="mx-5">Home</RouterLink>
      <RouterLink :to="{ name: 'product' }" class="mx-5">Product</RouterLink>
      <RouterLink :to="{ name: 'about' }" class="mx-5">About</RouterLink>
    </div>
  </header>

  <RouterView />
</template>

<script setup>
import { RouterView } from 'vue-router';
import 'bootstrap';

import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
</script>

<template>
  <Header />
  <main class="container my-4">
    <RouterView />
  </main>
  <Footer />
</template>

<style>
@import 'bootstrap';
@import '@/assets/base.css';
</style>

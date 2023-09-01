<script setup>
import Navbar from '../components/Navbar.vue';
import Destiantions from '../components/Destinations.vue';
import Jumbotron from '../components/Jumbotron.vue';
import KekayaanAlam from '../components/KekayaanAlam.vue';
import Profil from '../components/Profil.vue';
import AdatIstiadat from '../components/adatIstiadat.vue';
import RumahAdat from '../components/RumahAdat.vue';
import Footer from '../components/Footer.vue';
import Berita from '../components/Berita.vue';
</script>

<template>
  <header>
    <Navbar />
  </header>
  <Jumbotron />
  <Profil />
  <AdatIstiadat />
  <RumahAdat />
  <Destiantions />
  <KekayaanAlam />
  <Berita />
  <Footer />
</template>

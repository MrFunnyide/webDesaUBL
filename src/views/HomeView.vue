<script setup>
import Navbar from '../components/Navbar.vue';
import Destiantions from '../components/Destinations.vue';
import Jumbotron from '../components/Jumbotron.vue';
import KekayaanAlam from '../components/KekayaanAlam.vue';
import Profil from '../components/Profil.vue';
import Sejarah from '../components/Sejarah.vue';
import AdatIstiadat from '../components/adatIstiadat.vue';
import RumahAdat from '../components/RumahAdat.vue';
import Footer from '../components/Footer.vue';
</script>

<template>
  <header>
    <Navbar />
  </header>
  <Jumbotron />
  <Profil />
  <Sejarah />
  <AdatIstiadat />
  <RumahAdat />
  <Destiantions />
  <KekayaanAlam />
  <Footer />
</template>

<template>
  <div>
    <Navbar></Navbar>
    <br>
    <Header></Header>
    <br>
    <center><Mid></Mid></center>
    <br>
    <hr>
    <center><SectionSatu></SectionSatu></center>
    <br>
    <hr>
    <center><SectionDua></SectionDua></center>
    <br>
    <hr>
    <Footer></Footer>

  </div>
</template>
<script setup>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import Mid from './components/Mid.vue';
import Footer from './components/Footer.vue';
import SectionSatu from './components/SectionSatu.vue';
import SectionDua from  './components/SectionDua.vue';
</script>


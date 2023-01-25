<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi Desa Padurenan adalah "TERWUJUDNYA DESA PADURENAN YANG MAJU, SEJAHTERA, BERPRESTASI, BERBUDAYA, BERDAYA KARYA, DAN BERAKHLAK MULIA"</p>
      <p>Misi Desa Padurenan diantaranya yaitu 1.Mewujudkan dan mengembangkan kegiatan keagamaan untuk menambah keimanan dan ketaqwaan kepada Tuhan Yang Maha Esa</p>
      <p>2.Membangun dan meningkatkan hasil pertanian dengan jalan penataan perairan, perbaikan jalan sawah/jalan usaha tani, pola pemupukan, dan tanian yang baik</p>
      <p>3.Menata pemerintahan Desa Padurenan yang kompak dan bertanggung jawab dalam mengemban amanat masyarakat</P>
        <p>4.Meningkatkan pelayanan masyarakat secara terpadu dan optimal</p>
        <p>5.Menumbuh kembangkan kelompok tani dan gabungan kelompok tani serta bekerjasama dengan HIPPA untuk memfasilitasi kebutuhan petani</p>
        <p>6.Menumbuh kembangkan usaha kecil dan menengah</p>
        <p>7.Membangun dan mendorong majunya bidang pendidikan baik formal maupun non formal yang mudah di akses dan dinikmati seluruh warga masyarakat tanpa terkecuali yang mampu menghasilkan insan intelektual</p>
        <p>8.Membangun dan mendorong usaha-usaha untuk pengembangan dan optimalisasi sektor pertanian, peternakan, dan ke wirausahaan</p>
      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/desa-padurenan.jpeg" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>

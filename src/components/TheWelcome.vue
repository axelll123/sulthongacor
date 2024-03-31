<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>PENDIDIKAN</template>

    Saat ini saya kuliah di salah satu Kampus swasta di Riau yaitu
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    .
    Sebelumnya saya bersekolah di SMK SWASTA
    <a href="https://www.smkakbar.sch.id/profil-sekolah" target="_blank" rel="noopener">AKBAR PEKANBARU</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat, Tanggal Lahir</template>

    Saya Lahir di sebuah kota kecil di Provinsi <a href="https://id.wikipedia.org/wiki/Sumatera_Utara" target="_blank" rel="noopener"
      >Sumatera Utara</a>
      yaitu 
    <a href="https://id.wikipedia.org/wiki/Dolok_Masihul,_Serdang_Bedagai" target="_blank" rel="noopener"
      >Kota Dolok Masihul</a
    >.pada tanggal
     04 Juli 2004
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    Prodi atau Jurusan Kuliah
Saya mengambil Program didik Teknik Informatika atau biasa disebut IT
    , sekarang saya berada di semester 4 dan berada di kelas paling gacor yaitu
    <a href="https://www.instagram.com/dobleh_a22/" target="_blank" rel="noopener">Dobleh A22</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya lampirkan sebagai berikut : <br />
    1.
    <a href="https://www.instagram.com/p/C5D0WnMyUc5/?igsh=MXF4bnQ4eDFjOGxkMQ==" target="_blank" rel="noopener"
      >NGOBRUT(NGODING BRUTAL)</a
    ><br />
    2. <a href="https://cdn.gramedia.com/uploads/items/psychology_of_money.jpg" target="_blank" rel="noopener"
      >Membaca Buku</a> <br/>
    3.  <a href="https://www.instagram.com/p/C3fhehsv-AR/?igsh=ZXg1bDdhZzU2N29s" target="_blank" rel="noopener"
      >Ngopi</a> <br/>
    4. <a href="https://www.youtube.com/watch?v=10pvNtNoQs8&pp=ygUfYmVsYWphciBtZWxlcGFza2FuIGRpcmlueWEgcmVmZg%3D%3D" target="_blank" rel="noopener"
      >Belajar</a> </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>

    Saya lumayan aktif di sosial media dengan tujuan untuk meroastink orang,sarkas mencari informasi serta berkeluh kesah.<br />
    Instagram = @<a href="https://www.instagram.com/sulthonafl/" target="_blank" rel="noopener"
      >sulthonafl</a
    > <br/>
    Facebook = @<a href="https://www.facebook.com/profile.php?id=100007430744680&mibextid=eQY6cl" target="_blank" rel="noopener"
      >Sulthon Abiyyiaflah</a
    >.
  </WelcomeItem>
</template>
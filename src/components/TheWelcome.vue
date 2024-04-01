<script setup lang="ts">
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
    <template #heading>Tentang Saya</template>
    Saya adalah mahasiswa di kampus universitas islam riau yang berada di jalan Kaharuddin Nst
    Pekanbaru. Saat ini saya mengambil jurusan Teknik Informatika Universitas Islam Riau dan sekarang saya berada di semester 4 .
    Saya Berasal dari Kecamatan tualang, Kabupaten siak, Provinsi Riau
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    SDN 010 TUALANG 2010-2016<br />
    SMPN 2 TUALANG 2016-2019<br />
    SMAN 5 TUALANG 2019-2022<br />
    UNIVERSITAS ISLAM RIAU 2022-NOW
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Pernah Menjadi Anggota Osis <br />
    Pernah Menjadi Anggota Paskibra <br />
    Pernah Menjadi Anggota Remaja Mesjid <br />
    <ul>
      
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
     
      <li>HTML</li>
      <li>PHP</li>
      <li>C++</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hubungi Saya</template>

    Instagram :<a href="https://www.instagram.com/raihanktsr_/" target="_blank">raihanktsr_ </a
    ><br />
    Email : raihankautsar57@gmail.com<br />
    No HP : 082286695810
  </WelcomeItem>
</template>
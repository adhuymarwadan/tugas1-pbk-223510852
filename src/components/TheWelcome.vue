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
    <template #heading>Pendidikan</template>

    <a href="https://vuejs.org/" target="_blank" rel="noopener">SDN 12 Air Jamban</a> 2010 - 2016<br />
    <a href="https://vuejs.org/" target="_blank" rel="noopener">SMPN 10 Mandau</a> 2016 - 2019<br />
    <a href="https://vuejs.org/" target="_blank" rel="noopener">SMAN 10 Mandau</a> 2019 - 2022<br />
    <a href="https://vuejs.org/" target="_blank" rel="noopener">Universitas Islam Riau</a> 2022 -
    2026 InsyaAllah
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya adalah berolahraga yaitu futsal dan badminton, hobi saya yang lain yaitu bermain alat
    musik contohnya gitar dan bass, Yang saya tidak bisa adalah berenang karena saya sering
    tenggelam ketika bermain dikolam berenang.

    <br />

    Jika ada perlombaan berenang saya juara 1. juara 1 tenggelam xixixi.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skils</template>

    Saya memiliki sedikit skils atau kemampuan di database, c++ , html, css dan javascript. Tapi
    masih dalam tahap belajar dibagian javascript dan vue js.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>

    Jika teman-teman ada yang ingin berteman silahkan hubungi kontak dibawah : <br />
    Whatsapp : 089652317572 <br />
    Instagram : @yudhaadrmwn
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Penutup</template>

    Untuk teman-teman terimakasih sudah berkunjung diweb portofolio saya yang sebenarnya dibuat
    untuk memenuhi tugas kuliah. <br />
    Thankyou, Be Yourself And Never Surrender.
  </WelcomeItem>
</template>

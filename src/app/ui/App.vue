<script setup lang="ts">
import Header from '@/shared/ui/layout/Header.vue'
import Footer from '@/shared/ui/layout/Footer.vue'
import MainContainer from '@/shared/ui/layout/MainContainer.vue'
</script>

<template>
  <Header/>
  <MainContainer>
    <router-view/>
  </MainContainer>
  <Footer/>
</template>

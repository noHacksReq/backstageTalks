<script setup lang="ts">
import { ref } from 'vue'
import Body from './components/Body.vue';
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

</script>

<template>
  <div>
    <Header />
    <Body  imgSrc="https://picsum.photos/200/300"/>
    <Body  imgSrc="https://picsum.photos/200/300"/>
    <Body  imgSrc="https://picsum.photos/200/300"/>
    <Body  imgSrc="https://picsum.photos/200/300"/>
    <Footer />
  </div>
</template>

<style scoped>

template {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

</style>

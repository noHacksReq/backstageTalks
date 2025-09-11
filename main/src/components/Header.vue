<script setup lang="ts">
import { ref } from 'vue'


</script>

<template>
  

  <div class="headerCont">
    <h1 class="title">BACKSTAGE TALKS</h1>
    <a class="email" href="mailto: something@example.com">info@backstagetalks.com</a>
  </div>

</template>

<style scoped>
.headerCont {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-family: Helvetica, sans-serif;
  font-weight: 400;
}

.title {
  font-weight: 900;
}

.email {
  color: black;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 21px;
  font-weight: 600;
}
</style>

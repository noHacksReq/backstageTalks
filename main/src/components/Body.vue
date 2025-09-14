<script setup lang="ts">
import { ref, defineProps } from 'vue'

const props = defineProps(['imgSrc'])

</script>

<template>
  <div class="bodyCont">
    <img class="mainImg" alt="main image" :src="imgSrc"/>
    <p class="issue">Issue #1</p>
    <a href="#####">Buy Here</a>
    <span>
      <p>Or in <a href="#####">Selected Stores</a></p>
    </span>
    
    
  </div> 
</template>

<style scoped>

a {
  color: white;
  text-decoration: none;
}

.bodyCont {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 30%;
  margin: 0 auto;
  padding-top: 2%;

}

.mainImg {
  height: 500px;
  width: 420px;
}

.issue {
  margin: 0;
}
</style>

<script setup lang="ts">
import { ref } from 'vue'


</script>

<template>
  <div class="footerCont">
    <h3 class="info">Backstae Talks is a magazine
      of casual, but in depth dialogues
      on design and business. Our decisions
      shape and influence this complex 
      world-to have a chance to make the
      right ones, we need to Talk<br/>
      <span class="studioLink">&copy; 2021 <a
        href="https://buromilk.com/"
        >Published by studio milk</a></span><br/>
        <a class="privacy"
        href="https://buromilk.com/"
        >Privacy Policy</a>
    </h3>
    <ul class="issueList">
      <li>Issue #5</li>
      <li>Issue #4</li>
      <li>Issue #3</li>
      <li>Issue #2</li>
      <li>Issue #1</li>
    </ul>
  </div>

</template>

<style scoped>
a {
  color: black;
}
.footerCont {
  display: flex;
  justify-content: space-between;
  font-family: Arial, Helvetica, sans-serif;
}

.info {
  width: 20%;
  display: flex;
  flex-direction: column;
  text-align: start;
}

.studioLink {
  font-weight: 100;
}

.issueList {
  list-style: none;
  display: flex;
  flex-direction: column;
  justify-content: end;
}

.issueList li {
  font-size: 20px;
  margin: 10px;
}

.privacy {
 
 text-decoration: none;
}
</style>

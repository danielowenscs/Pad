<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
<div class="header">
</div>
<div class="content">
  <RouterView/>
</div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Inter');
.header {
  text-align: center;
  background: #358A66;
  color: white;
  font-size: 30px;
  width: 100%;
  height: 64px;
}
.content {
 width: 1180px; 
  margin-left: calc((100% - 1180px)/2);
}
</style>
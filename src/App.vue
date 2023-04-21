<template>
  <div class="resume">
    <personal-information></personal-information>
    <skills></skills>
    <company-project></company-project>
    <warbler-fe></warbler-fe>
    <educational></educational>
  </div>
</template>

<script setup lang="ts">
import personalInformation from './components/personal-information.vue';
import skills from './components/skills.vue';
import warblerFe from './components/wabler-fe.vue';
import companyProject from './components/company-project.vue';
import educational from './components/educational.vue';
</script>

<style lang="scss">
body,
html,
#app {
  width: 100%;
  height: 100%;
  background: #eee;
  font-size: 16px;
}
.resume {
  width: 800px;
  min-height: 100%;
  background: #fff;
  margin: 0 auto;
  overflow: auto;
  padding: 16px;
}
strong {
  font-size: 14px;
  color: #f60;
  padding: 0 5px;
  margin: 0;
}
.circle {
  font-size: 12px;
  display: inline-block;
  transform: scale(3);
  margin-right: 8px;
  color: #333;
}
</style>

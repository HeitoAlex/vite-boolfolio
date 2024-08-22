<script setup>

  import ProjectList from './components/ProjectList.vue';
  
</script>

<template>
  <ProjectList/>
  <router-view></router-view>
</template>

<style lang="scss">
  @use './styles/general.scss';

</style>

<script>
import ProjectDescription from './components/ProjectDescription.vue';

export default {
  name: 'App',
  components: {
    ProjectDescription,
  },
};
</script>

<template>
  <div id="app">
    <ProjectDescription />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 40px;
}
</style>
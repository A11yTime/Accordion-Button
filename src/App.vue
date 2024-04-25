<template>
  <StaticButton />
  <DynamicButton />
</template>
<script>
import StaticButton from './components/StaticButton.vue';
import DynamicButton from './components/DynamicButton.vue'

export default {
  name: 'App',
  components: {
    StaticButton,
    DynamicButton
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <NavBar />
    <router-view />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
export default {
  components: { NavBar },
};
</script>

<style></style>


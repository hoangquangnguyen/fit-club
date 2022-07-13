<template>
  <!-- <nav>
    <div class="text-4xl text-blue-700 font-bold">Hell oooo</div>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view /> -->
  <sector-one />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}
</style>
<script lang="ts">
import SectorOne from "./views/SectorOne.vue";
export default {
  components: { SectorOne },
  setup() {
    return {};
  },
};
</script>

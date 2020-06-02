<template>
  <div id="app">
    <div id="nav">
      <top-nav-bar></top-nav-bar>
    </div>
    <router-view />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
  components: {
    "top-nav-bar": Navbar
  }
};
</script>

<style lang="scss"></style>

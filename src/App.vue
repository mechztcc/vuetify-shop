<template>
  <Navbar />
  <router-view />
</template>

<script lang="ts" setup>
import Navbar from "./modules/shared/components/Navbar.vue";

components: {
  Navbar;
}
</script>

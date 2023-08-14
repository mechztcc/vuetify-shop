<template>
  <NavbarVue />
  <router-view />
</template>

<script lang="ts" setup>
import NavbarVue from "./modules/shared/components/navbar.vue";
components: {
  NavbarVue;
}
</script>

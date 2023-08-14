<template>
  <v-card class="pa-3">
    <FilterByPriceRange />
  </v-card>
</template>
<script lang="ts">
import FilterByPriceRange from "./FilterByPriceRange.vue";
export default {
  name: "FiltersContainerComponent",
  components: {
    FilterByPriceRange,
  },
  data() {
    return {};
  },
};
</script>
<style lang=""></style>

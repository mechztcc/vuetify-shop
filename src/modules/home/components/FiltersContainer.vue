<template>
  <v-card class="pa-3">
    <FilterByPriceRange />
    <FiltersByCategory />
  </v-card>
</template>
<script lang="ts">
import FilterByPriceRange from "./FilterByPriceRange.vue";
import FiltersByCategory from "./FiltersByCategory.vue";
export default {
  name: "FiltersContainerComponent",
  components: {
    FilterByPriceRange,
    FiltersByCategory,
  },
  data() {
    return {};
  },
};
</script>
<style lang=""></style>

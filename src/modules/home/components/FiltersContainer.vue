<template>
  <v-card class="pa-3">
    <FilterByPriceRange />
    <FiltersByCategory />
    <FilterByMark />
  </v-card>
</template>
<script lang="ts">
import FilterByPriceRange from "./FilterByPriceRange.vue";
import FiltersByCategory from "./FiltersByCategory.vue";
import FilterByMark from "./FilterByMark.vue";
export default {
  name: "FiltersContainerComponent",
  components: {
    FilterByPriceRange,
    FiltersByCategory,
    FilterByMark,
  },
  data() {
    return {
    };
  },
};
</script>
<style lang=""></style>

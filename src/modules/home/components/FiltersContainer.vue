<template>
  <v-card class="pa-10">
    <FilterByPriceRange />
    <FiltersByCategory />
    <FilterByMark />
    <FilterByConditionVue />
  </v-card>
</template>
<script lang="ts">
import FilterByPriceRange from "./FilterByPriceRange.vue";
import FiltersByCategory from "./FiltersByCategory.vue";
import FilterByMark from "./FilterByMark.vue";
import FilterByConditionVue from './FilterByCondition.vue';
export default {
  name: "FiltersContainerComponent",
  components: {
    FilterByPriceRange,
    FiltersByCategory,
    FilterByMark,
    FilterByConditionVue
  },
  data() {
    return {
    };
  },
};
</script>
<style lang=""></style>

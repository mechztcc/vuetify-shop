<template>
  <div>
    <h5 class="mb-8">Price:</h5>
    <v-range-slider v-model="value" color="primary" thumb-label="always"></v-range-slider>
  </div>
</template>
<script lang="ts">
export default {
  name: "FiltersByPriceRangeComponent",
  data() {
    return {
      value: [0, 100],
    };
  },
};
</script>
<style lang=""></style>

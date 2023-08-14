<template>
  <div>
    <h5>Condition:</h5>
    <v-checkbox
      :label="item"
      v-for="(item, index) in conditions"
      :key="index"
    ></v-checkbox>
  </div>
</template>
<script lang="ts">
export default {
  name: "FilterByConditionComponent",
  data() {
    return {
      conditions: ["New", "Used", "Recondicioned"],
    };
  },
};
</script>
<style lang=""></style>

<template>
  <div>
    <h5>Mark</h5>
    <v-checkbox :label="item" v-for="(item, index) of items" :key="index" />
  </div>
</template>
<script lang="ts">
export default {
  name: "FilterByMarkComponent",
  data() {
    return {
      items: ["Samsung", "Xiaomi", "Motorola", "Apple", "Nokia"],
    };
  },
};
</script>
<style lang=""></style>

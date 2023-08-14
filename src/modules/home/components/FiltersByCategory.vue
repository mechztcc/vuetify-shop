<template>
  <div>
    <v-combobox
      chips
      dense
      variant="outlined"
      label="Categoria"
      :items="items"
      multiple
    ></v-combobox>
  </div>
</template>
<script lang="ts">
export default {
  name: "FiltersByCategoryComponent",
  data() {
    return {
      items: ["Headphone", "Smartphone", "Mouse"],
    };
  },
};
</script>
<style lang="scss"></style>

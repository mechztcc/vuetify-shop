<template>
  <div>
    <v-container>
      <v-row>
        <v-col cols="12" md="3">
          <FiltersContainer/>
        </v-col>
        <v-col cols="12" md="3"> <CardProduct /> </v-col>
        <v-col cols="12" md="3"> <CardProduct /> </v-col>
        <v-col cols="12" md="3"> <CardProduct /> </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script lang="ts">
import CardProduct from "../components/CardProduct.vue";
import FiltersContainer from "../components/FiltersContainer.vue";
export default {
  name: "HomeLayout",
  components: {
    CardProduct,
    FiltersContainer
  },
  data() {
    return {};
  },
};
</script>
<style lang="scss"></style>

<template>
  <div class="mt-10">
    <v-container>
      <v-row>
        <v-col cols="12" md="3">
          <FiltersContainer />
        </v-col>
        <v-col cols="12" md="9">
          <v-row>
            <v-col
              cols="12"
              md="4"
              lg="4"
              v-for="(item, index) in 6"
              :key="index"
            >
              <CardProduct />
            </v-col>
          </v-row>
        </v-col>
      </v-row>
      <div class="mt-12 mb-10 text-end">
        <v-pagination :length="6"></v-pagination>
      </div>
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
    FiltersContainer,
  },
  data() {
    return {};
  },
};
</script>
<style lang="scss"></style>

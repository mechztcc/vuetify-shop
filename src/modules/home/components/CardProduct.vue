<template>
  <v-card class="pa-4">
    <div class="d-flex justify-center">
      <img class="img" src="@/assets/imgs/headphone.jpg" alt="" />
    </div>
    <div class="d-flex justify-space-between">
      <v-card-title>SonicMax Pro X1</v-card-title>
      <v-card-title><sup>$</sup> 90,<sup>99</sup></v-card-title>
    </div>
    <v-card-text class="pb-0">Organic cottom</v-card-text>
    <v-card-text class="mt-0 pt-0"
      >Introducing the pinnacle of audio immersion - the cutting-edge headphones
      that redefine your auditory experience: The SonicMax Pro X1.</v-card-text
    >
    <v-card-text>
      <div class="d-flex justify-space-between align-center w-100">
        <v-rating
          :value="4.5"
          color="amber"
          size="20"
          dense
          half-increments
          readonly
        ></v-rating>
        <div class="grey--text">4.5 (413)</div>
      </div>
    </v-card-text>
    <v-card-actions>
      <v-btn color="primary">Add to car</v-btn>
    </v-card-actions>
  </v-card>
</template>
<script lang="ts">
export default {
  name: "CardProductComponent",
};
</script>
<style lang="scss">
.img {
  max-height: 300px;
  max-width: 100%;
  object-fit: cover;
}
</style>

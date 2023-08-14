<template>
  <v-card class="bg-primary" elevation="2">
    <v-container>
      <v-row>
        <v-col cols="3" md="3" class="d-flex align-center justify-start"> LOGO </v-col>
        <v-col cols="6" md="6" class="d-flex align-center justify-center">
          <v-text-field class="mb-0" variant="outlined" label="Search" prepend-inner-icon="mdi-magnify"/>
        </v-col>
        <v-col cols="3" md="3" class="d-flex align-center justify-end">
          <v-icon>mdi-menu</v-icon>
        </v-col>
      </v-row>
    </v-container>
  </v-card>
</template>
<script lang="ts">
export default {
  name: "NavbarComponent",
  data() {
    return {};
  },
};
</script>
<style lang="scss" scoped>
.logo {
  max-height: 80px;
  max-width: 80px;
}
</style>

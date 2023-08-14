<template>
  <v-card>
    <div class="d-flex justify-space-between pa-6 bg-primary">
      LOGO
      <v-icon>mdi-menu</v-icon>
    </div>
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

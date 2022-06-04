<template>
  <v-row>
    <v-col cols="8" class="frame-content px-6">
      <products></products>
    </v-col>
    <v-col cols="4">
      ORDERS
    </v-col>
  </v-row>
</template>

<style scoped>
html,
body {
  padding: 0;
  overflow: hidden !important;
}
.frame-content {
  height: 90vh;
  overflow-y: auto;
}
</style>

<template>
  <v-card class="mx-auto" width="100%">
    <v-app-bar color="secondary" dark>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title>{{ titleText }}</v-toolbar-title>
    </v-app-bar>
  </v-card>
</template>

<script>
export default {
  name: "Header",
  props: ["title"],
  setup({ title }) {
    return {
      titleText: title,
    };
  },
};
</script>

<template>
  <v-app>
    <v-system-bar color="secondary">
      System Bar
    </v-system-bar>

    <v-app-bar color="primary">
      <v-app-bar-title>
        Application Bar
      </v-app-bar-title>
    </v-app-bar>

    <v-navigation-drawer permanent>
      Navigation Drawer
    </v-navigation-drawer>

    <v-main>
      <v-container>
        Main Contents
      </v-container>
    </v-main>

    <v-bottom-navigation>
      Button Navigation
    </v-bottom-navigation>

    <v-footer color="primary" app>
      Footer
    </v-footer>

  </v-app>
</template>

<script setup>
definePageMeta({ layout: 'blank' })
</script>
<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import TestIcons from '../components/TestIcons.vue'
</script>

<template>
  <main>
    <TestIcons />
    <TheWelcome />
    <v-expansion-panels>
    <v-expansion-panel
      title="Title"
      text="Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ratione debitis quis est labore voluptatibus! Eaque cupiditate minima"
    >
    </v-expansion-panel>
  </v-expansion-panels>
  </main>
</template>

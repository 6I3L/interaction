<template>
  <v-app>
    <v-main>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script setup>
import * as d3 from "d3"

onMounted(async () => {
  const rawData = await d3.csv('taylorswift.csv');
  console.log(rawData);
});
  //
</script>

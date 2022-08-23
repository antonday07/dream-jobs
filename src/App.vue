<script setup lang="ts">

import TheWelcome from './components/TheWelcome.vue'
import Header from './components/Header.vue'
import ListJobs from './components/ListJobs.vue'
</script>

<template>
  <Header></Header>

  <main>
    <ListJobs></ListJobs>
  </main>
</template>

<style scoped lang="scss">

main {
  max-width: 960px;
  text-align: center;
}
</style>

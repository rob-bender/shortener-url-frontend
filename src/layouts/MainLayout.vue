<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script lang="js">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainLayout',
  setup() {
    return {}
  }
})
</script>

<style lang="scss" scoped></style>

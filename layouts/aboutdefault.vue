<template>
  <v-app>
    <v-main>
      <v-container fluid class="pa-0 ma-0">
        <Header/>
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Header from '@/components/Header'

export default {
  components: { Header }
}
</script>

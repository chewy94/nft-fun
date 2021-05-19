<template>
  <v-app>
    <v-app-bar>
      <v-app-bar-title>
        <div class="d-flex align-center">
          <v-icon style="font-size: 32px; margin-right: 12px" color="purple darken-2" large>mdi-file-document-edit-outline</v-icon>
          NFT FUN
        </div>
      </v-app-bar-title>
      <v-spacer />
      <v-btn class="mr-1" text>Marketplace</v-btn>
      <v-btn text>Stats</v-btn>
      <v-divider class="mx-4" inset vertical />
      <v-btn
        class="mr-1"
        icon="mdi-account-circle-outline"
        color="transparent"
      />
      <v-btn
        icon="mdi-wallet-outline"
        color="transparent"
      />
    </v-app-bar>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App'
})
</script>
<style lang="scss">
html {
  line-height: 1;
}
</style>

<template>
  <v-container>
    <v-row>
      <v-col>
        <div style="font-size: 48px">Discover, collect, and sell extraordinary NFTs</div>
        <div style="font-size: 24px">on the world's first & largest NFT marketplace</div>
        <div>
          <v-btn color="primary" flat>Explore</v-btn>
          <v-btn color="primary" outlined>Create</v-btn>
        </div>
      </v-col>
      <v-col>
        <v-sheet>
          <img src="https://thumbor.forbes.com/thumbor/fit-in/900x510/https://www.forbes.com/advisor/wp-content/uploads/2021/04/NFT.jpeg.jpg" />
        </v-sheet>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Home'
})
</script>

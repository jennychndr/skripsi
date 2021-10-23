<template>
  <v-card
    class="mx-auto"
    height=20%
    tile
  >
    <v-img
      height="250px"
      src="https://cdn.vuetifyjs.com/images/cards/server-room.jpg"
    >
      <v-row
        align="end"

      >
        <v-col
          align-self="start"
          class="pa-0"
          cols="12"
        >
          <v-avatar
            class="profile"
            color="grey"
            size="164"
            tile
          >
            <v-img src="https://cdn.vuetifyjs.com/images/profiles/marcus.jpg"></v-img>
          </v-avatar>
        </v-col>
        <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
            dark
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
                Marcus Obrien
              </v-list-item-title>

            </v-list-item-content>
          </v-list-item>
        </v-col>
      </v-row>
    </v-img>
  </v-card>
</template>

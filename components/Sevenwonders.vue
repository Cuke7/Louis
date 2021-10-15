<template>
  <v-row align="center" class="pa-4">
    <v-col order="2" order-md="1" cols="12" md="6" class="text-center">
      <v-img contain max-height="500" src="7W_mockup.png"></v-img>
    </v-col>
    <v-col order="1" order-md="2" cols="12" md="6" align-self="start">
      <v-row align="center">
        <v-col cols="auto">
          <div class="text-h2">
            7W
          </div>
        </v-col>
        <v-col cols="auto">
          <v-avatar size="70">
            <v-img src="icon_7W.png"></v-img>
          </v-avatar>
        </v-col>
      </v-row>

      <div class="text-body-1 mt-12 text-justify">
        Permet de distribuer aléatoirement les places et les merveilles de
        départ pour 7 wonders. Automatise et rend plus rapide le comptage des
        points. Affiche des statistiques de jeux.
      </div>

      <div class="text-md-left text-center">
        <v-btn
          color="#0083E5"
          class="mt-12"
          href="https://7w-app.netlify.app/"
          target="_blank"
        >
          Essayer 7W
        </v-btn>
      </div>
    </v-col>
  </v-row>
</template>

<template>
  <v-row align="center" class="pa-4">
    <v-col order="2" order-md="1" cols="12" md="6" class="text-center">
      <v-img contain max-height="500" src="auditere_mockup.png"></v-img>
    </v-col>
    <v-col order="1" order-md="2" cols="12" md="6" align-self="start">
      <v-row align="center">
        <v-col cols="auto">
          <div class="text-h2">
            Auditere
          </div>
        </v-col>
        <v-col cols="auto">
          <v-avatar size="70">
            <v-img src="icon_auditere.png"></v-img
          ></v-avatar>
        </v-col>
      </v-row>

      <div class="text-body-1 mt-12 text-justify">
        Permet de rechercher et lire de la musique sur Youtube tout en
        vérouillant le téléphone. Peut aussi enregistrer et lire des playlists
        crées sur Youtube.
      </div>

      <div class="text-md-left text-center">
        <v-btn
          color="#0083E5"
          class="mt-12"
          href="https://auditere.netlify.app"
          target="_blank"
        >
          Essayer Auditere
        </v-btn>
      </div>
    </v-col>
  </v-row>
</template>

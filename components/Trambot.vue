<template>
  <v-row align="center" class="pa-4" justify="center">
    <v-col order="2" order-md="2" cols="12" md="6" class="text-center">
      <v-img contain max-height="500" src="trambot_mockup.png"></v-img>
    </v-col>
    <v-col order="1" order-md="1" cols="12" md="4" align-self="start">
      <v-row align="center">
        <v-col cols="auto">
          <div class="text-h2">
            TramBot
          </div>
        </v-col>
        <v-col cols="auto">
          <v-avatar size="70">
            <v-img src="icon_trambot.png"></v-img>
          </v-avatar>
        </v-col>
      </v-row>

      <div class="text-body-1 mt-12 text-justify">
        Chatbot sur Messenger, permet d'obtenir les horaires des prochains
        passages pour les bus et trams, en fonction de l'arrêt demandé.
      </div>

      <div class="text-md-left text-center">
        <v-btn
          color="#0083E5"
          class="mt-12"
          href="https://m.me/TramBot-942749432783368"
          target="_blank"
        >
          Essayer TramBot
        </v-btn>
      </div>
    </v-col>
  </v-row>
</template>

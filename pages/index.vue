<template>
  <div class="mt-12">
    <!-- <div class="text-h1 text-center my-12">Mes projets</div> -->
    <div v-for="(app, index) in apps" :key="index">
      <Apps :projectData="app" :index="index" class="my-12"></Apps>
    </div>
    <div v-for="(project, index) in projects" :key="index">
      <CodeProjects
        :projectData="project"
        :index="index"
        class="my-12"
      ></CodeProjects>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    apps: [
      {
        titre: "Quotidie",
        icon_url: "icon_quotidie.png",
        description:
          "Reçois tous les jours à 9h l'évangile du jour ! Quotidie te donne aussi le saint du jour et un recueil de prières.",
        mockup_url: "quotidie_mockup.png",
        url: "https://quotidie.fr"
      },
      {
        titre: "Auditere",
        icon_url: "icon_auditere.png",
        description:
          "Permet de rechercher et lire de la musique sur Youtube tout en vérouillant le téléphone. Peut aussi enregistrer et lire des playlists crées sur Youtube.",
        mockup_url: "auditere_mockup.png",
        url: "https://auditere.netlify.app"
      },
      {
        titre: "D&D app",
        icon_url: "icon_dnd.png",
        description:
          "Application pour D&D 5E, permet de trouver rapidement un sort ou un object magique. Possibilité de faire une recherche filtrée.",
        mockup_url: "dnd_mockup.png",
        url: "https://dnd-app.netlify.app"
      },
      {
        titre: "7W",
        icon_url: "icon_7W.png",
        description:
          "Permet de distribuer aléatoirement les places et les merveilles de départ pour 7 wonders. Automatise et rend plus rapide le comptage des points. Affiche des statistiques de jeux.",
        mockup_url: "7W_mockup.png",
        url: "https://7w-app.netlify.app"
      },
      {
        titre: "Trambot",
        icon_url: "icon_trambot.png",
        description:
          "Chatbot sur Messenger, permet d'obtenir les horaires des prochains passages pour les bus et trams, en fonction de l'arrêt demandé. NE FONCTIONNE PLUS, à cause de la super politique de Facebook concernant les chatbots...",
        mockup_url: "trambot_mockup.png",
        url: "https://m.me/TramBotBordeaux"
      },
      {
        titre: "BBsit",
        icon_url: "icon_bbsit.png",
        description: "Permet de créer et partager des babysittings.",
        mockup_url: "bbsit_mockup.png",
        url: "https://bbsitapp.netlify.app"
      }
    ],
    projects: [
      {
        titre: "Boids",
        descriptionHtml:
          "Simulation de vol d'un groupe d'oiseaux. Inspiré de <a style = 'color: white;' href='https://www.youtube.com/watch?v=bqtqltqcQhw' target='_blank'>https://www.youtube.com/watch?v=bqtqltqcQhw</a>. A consulter sur ordinateur pour conserver la mise en page.",
        url: "https://cuke7.github.io/Boids/"
      },
      {
        titre: "Conjecture de Collatz",
        descriptionHtml:
          "Illustration de la conjecture de Collatz, inspiré de <a style = 'color: white;' href='https://www.youtube.com/watch?v=094y1Z2wpJg' target='_blank'>https://www.youtube.com/watch?v=094y1Z2wpJg</a>. A consulter sur ordinateur pour conserver la mise en page.",
        url: "https://cuke7.github.io/CollatzConjecture/"
      }
    ]
  })
};
</script>

<style>
.v-main {
  background-image: linear-gradient(
    to right top,
    #3a46c9,
    #0072e1,
    #008ed2,
    #00a3ad,
    #00b389
  );
}
</style>

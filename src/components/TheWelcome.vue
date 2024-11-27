<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Quelques informations sur moi</template>
    <p>
      👨‍💻 Je suis Product Manager Freelance. <strong>(SCRUM / SAFe / Lean Six Sigma)</strong><br/>
      🎓 <strong>Certifié</strong> Lean Six Sigma Black Belt.<br/>
      ⚙️ <strong>+100</strong> projets IT gérés / <strong>+30</strong> projets PHP/Python/Vue.js développés.<br/>
      🧑‍💼 <strong>+6</strong> d'expériences.<br/>
      🇬🇧 Je parle <strong>Anglais couramment</strong>.<br/>
      🎾 Je suis passionné de sport, notamment de tennis.<br/>
      ✍️ J’écris des romans et des livres pratiques à mes heures perdues. (Dark Fantasy et Dev Perso).<br/>
      👮‍♂️ <strong>Fun fact :</strong> J'ai été Gendarme en unité d'intervention pendant 3 ans.<br/>
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pourquoi faire appel à moi en qualité de Product Manager ?</template>
    <ul>
      <li>Product Manager <strong>spécialisé dans l'IT</strong> depuis 6 ans.</li>
      <li>Identifier, comprendre et anticiper <strong>les besoins des utilisateurs</strong> afin d'optimiser la valeur ajoutée du produit.</li>
      <li><strong>Déterminer, rédiger et prioriser</strong> les fonctionnalités produits.</li>
      <li>Réalisation des <strong>spécifications fonctionnelles et techniques</strong>.</li>
      <li><strong>Mise en place et suivi des méthodologies agiles</strong> SCRUM et Lean Six Sigma. (Daily, sprints, reviews, backlog, planning).</li>
      <li><strong>Animation et management</strong> d'équipe d'ingénieurs.</li>
      <li><strong>Accompagnement</strong> des utilisateurs finaux. (Utilisation/support/incidents).</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Ma boite à outil</template>
    <ul>
      <li><strong>Méthodes agiles</strong>. (SCRUM, SAFe, Lean Six Sigma)</li>
      <li><strong>Management</strong> d'équipe IT.</li>
      <li>Compréhension fine de la <strong>programmation</strong>. (Ancien développeur).</li>
      <li><strong>Communication</strong>.</li>
      <li><strong>Outils :</strong> JIRA, Confluence, ClickUp, Gitlab, Mattermost, Teams ...</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>On travaille ensemble ?</template>

    <p>
      J'interviens aux alentours de <strong>Bordeaux + Full remote</strong>. <br/>
      Contact via mon profil : <a href="https://www.malt.fr/profile/nicolasgadeyne" target="_blank" rel="noopener">Malt</a>.
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Ils m'ont fait confiance</template>
    <p>
      France Travail, DILCRAH, E-Santé Occitanie, RFI, Business France, 
      French healthcare, French Fab, Harfanglab, AFPOLS...
    </p>
  </WelcomeItem>
</template>

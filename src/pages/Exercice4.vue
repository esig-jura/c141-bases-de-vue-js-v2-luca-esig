<template>
  <v-container max-width="700">
    <!-- Donnée de l'exercice -->
    <exercice-objectifs number="4" />
    <!-- Zone de travail pour l'exercice -->
    <div class="exe-zone">
      <h2>Zone d'exercice</h2>
      <v-card class="mx-auto my-6 pa-2" max-width="500">
        <v-card-title>Saisie avec limite de caractères</v-card-title>

        <v-card-subtitle>
          Caractères restants :
          <strong>{{reste}}</strong>
        </v-card-subtitle>

        <v-card-text>
          <v-alert v-if="isTooLong" type="error" class="mb-2">
            Vous avez atteint la limite maximale de caractères !
          </v-alert>

          <v-text-field
            ref="textField"
            v-model="userInput"
            outlined
            rows="2"
            label="Tapez votre texte ici"
            :counter="MAX_LENGTH"
          />
        </v-card-text>

        <v-card-actions>
          <v-btn @click="userClick" color="primary">
            Activer le champ de texte
          </v-btn>
        </v-card-actions>
      </v-card>
    </div>
  </v-container>
</template>

<script setup>
// Importation du composant contenant la donnée de l'exercice
import ExerciceObjectifs from "@/components/ExerciceObjectifs.vue";
// Importation de la fonction réactive ref
import { ref,computed } from 'vue';
const textField = ref(null);
// Constante pour la limite de caractères
const MAX_LENGTH = 20;

const reste = computed(() => {
 return MAX_LENGTH - userInput.value.length;
})
// Variable réactive pour le texte saisi
const userInput = ref('');

const userClick = () => textField.value.focus();


const isTooLong = computed(() => {
  return userInput.value.length> MAX_LENGTH
})

</script>

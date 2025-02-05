<template>
  <h1>Exercice 5</h1>
  <div class="exe-objectifs">
    <h2>Objectifs</h2>
    <ul>
      <li>
        Apprendre à utiliser les <strong>watchers</strong>
        pour surveiller les changements d’une variable réactive.
      </li>
      <li>
        Afficher dynamiquement le nombre de caractères saisis
        dans la variable <code>userInput</code> à la place de
        <code>*** CARACTÈRES SAISIS ***</code>.
      </li>
      <li>
        Surveiller avec un <strong>watcher</strong>
        la saisie utilisateur, la variable
        <code>userInput</code>
        et afficher un message <code>&lt;v-alert&gt;</code>
        lorsque le texte contient le mot <strong>"Pokémon"</strong>
        en ignorant la casse (majuscules/minuscules).
      </li>
      <li>
        Dans le même <strong>watcher</strong>, réinitialiser
        automatiquement la saisie, mettre une chaîne vide,
        si elle dépasse la longueur maximale <code>MAX_LENGTH</code>.
      </li>
    </ul>
  </div>
</template>

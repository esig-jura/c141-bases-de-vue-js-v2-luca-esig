<template>
  <h1>Exercice 4</h1>
  <div class="exe-objectifs">
    <h2>Objectifs</h2>
    <ul>
      <li>
        Utiliser la directive <code>v-model</code> pour lier
        le champ de texte <code>&lt;v-text-field&gt;</code> à une
        variable <code>userInput</code>.
      </li>
      <li>
        Utiliser une <strong>propriété calculée (computed)</strong>
        pour afficher
        dynamiquement le nombre de caractères restants
        par rapport à la limite de caractères <code>MAX_LENGTH</code>.
      </li>
      <li>
        Afficher dynamiquement la valeur de la <strong>propriété
        calculée</strong> à la place du texte <code>*** CARACTÈRES
        RESTANTS ***</code>.
      </li>
      <li>
        Afficher le message d'avertissement <code>&lt;v-alert&gt;</code>
        si l'utilisateur dépasse la limite de caractères.
      </li>
      <li>
        Utiliser une <strong>référence (ref)</strong> pour accéder
        au champ de texte <code>&lt;v-text-field&gt;</code>
        et mettre le focus dessus en cliquant sur
        le bouton <code>Activer le champ de texte</code>.
      </li>

    </ul>
  </div>
</template>

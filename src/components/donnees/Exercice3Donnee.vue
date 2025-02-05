<template>
  <h1>Exercice 3</h1>
  <div class="exe-objectifs">
    <h2>Objectifs</h2>
    <ul>
      <li>Créer une liste dynamique de Pokémons basée sur la variable
        <code>pokemons</code> qui contient un <strong>tableau
          de noms de Pokémons</strong>.
      </li>
      <li>Utiliser la directive <code>v-for</code> pour parcourir le tableau
        de Pokémons et créer dynamiquement
        les éléments de la liste <code>&lt;v-list-item
          &gt;</code>.
      </li>
      <li>
        Utiliser <code>index</code>, position dans le tableau,
        comme clé <code>:key="index"</code>
        de la directive <code>v-for</code> pour identifier chaque élément
        de la liste.
      </li>
      <li>
        Remplacer le texte <code>*** POKEMON ***</code> par le nom du Pokémon
        parcourus dans la boucle <code>v-for</code>.
      </li>
      <li>Ecouter l'événement <code>click</code> sur le bouton de suppression
        pour appeler la fonction <code>removePokemon(index)</code> et ainsi
        supprimer le Pokémon.
      </li>
      <li>Afficher le message <code>"La liste est vide"</code> uniquement
        si le tableau ne contient plus de Pokémons. Sinon, afficher la liste
        des Pokémons.
      </li>
    </ul>
  </div>
</template>

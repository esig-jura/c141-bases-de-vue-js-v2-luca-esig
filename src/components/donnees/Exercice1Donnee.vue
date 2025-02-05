<template>
  <h1>Exercice 1</h1>
  <div class="exe-objectifs">
    <h2>Objectifs</h2>
    <ul>
      <li>
        Rendre le <strong>titre de la carte dynamique</strong> en utilisant le
        texte de la
        variable <code>title</code> pour remplacer <code>*** TITRE ***</code>.
      </li>
      <li>
        Rendre la <strong>description de la carte dynamique</strong> en
        utilisant le texte de
        la variable <code>description</code>
        pour remplacer <code>*** DESCRIPTION ***</code>.
      </li>
      <li>
        Changer dynamiquement la <strong>couleur du texte</strong> de la
        description en
        fonction de
        la valeur de <code>isHighlighted</code> :
        <ul>
          <li><code>blue</code> si <code>isHighlighted</code> est
            <code>true</code>.
          </li>
          <li><code>black</code> si <code>isHighlighted</code> est
            <code>false</code>.
          </li>
        </ul>
      </li>
      <li>
        Ajouter un événement <code>click</code> sur le <strong>bouton</strong>
        qui inverse
        la valeur <code>true/false</code> de <code>isHighlighted</code>.
      </li>
      <li>
        Faire en sorte que le <strong>texte du bouton</strong> change
        dynamiquement :
        <ul>
          <li>Afficher <code>"Réinitialiser la couleur"</code> si <code>
            isHighlighted</code> est <code>true</code>.
          </li>
          <li>Afficher <code>"Mettre en surbrillance"</code> si <code>
            isHighlighted</code> est <code>false</code>.
          </li>
        </ul>
      </li>
      <li>
        <strong>Suggestion</strong> : Utilisez des outils comme <strong>Vue
        DevTools</strong> pour modifier les valeurs de vos données et observer
        les changements dynamiques sur la carte.
      </li>
      <li>
        <strong>Astuce :</strong> Vous pourriez avoir besoin de rendre
        <strong>réactives</strong> les variables
        <code>isHighlighted</code>, <code>title</code> et <code>
        description</code>.
      </li>
    </ul>
  </div>
</template>

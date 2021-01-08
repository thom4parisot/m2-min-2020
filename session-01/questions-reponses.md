
# Questions et réponses

## Les questions et hésitations restées sans réponse (matin)

- Ça veut dire quoi `<li>` ?<br>
  Ça veut dire "list item". C'est généralement contenu dans un `<ol>` (ordered list) ou `<ul>` (unordered list).
  
- Comment faire des colonnes :)<br>
  Ça se fait en CSS. Avec `CSS Grid` ou `CSS Flex`.
  Si la donnée est tabulaire (genre un CSV/truc à la Excel), alors `<table>` est la balise par laquelle commencer.

- Comment faire une grille ?<br>
  Idem, ça se fait en CSS. Avec `CSS Grid`.
  
- Comment déplacer un élément ?<br>
  Avec l'attribut `draggable`… et pas mal de JavaScript. Cf. https://developer.mozilla.org/fr/docs/Web/API/API_HTML_Drag_and_Drop.
  Voir cet exemple https://web.dev/drag-and-drop/ didactique.
  Et cet autre exemple https://park.glitch.me/ ([code source](https://glitch.com/edit/#!/remix/park)).

- Comment récupérer le texte donné par l'utilisateur pour ensuite créer une carte?<br>
  Avec la balise `<input type="text">` et/ou `<textarea></textarea>`.

- Comment avoir une boucle entre la création d'une nouvelle liste et la création des colones

- Comment afficher les div inline ? Doit-on utiliser `<span>` ?<br>
  C'est ça : `<div>` prend toute la largeur (block) et `<span>` juste la taille du contenu (inline).
  Ce sont les balises les plus génériques. D'autres ont un sens (sémantique) plus précis, selon le cas d'usage.
  `<strong>`, `<i>` : inline.
  `<h1>`, `<h2>` : block<br>
  https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements et https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements

- Comment sauvegarder / garder les données écrites par l'utilisateur sans js ? <br>
  "Garder", on ne peut pas. Mais il y a `<form>`, pour envoyer les données par email.
  Avec JS, localement, y'a [`localstorage`](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).

- Comment mettre en forme un div précisément (faire une barre, une colonne)<br>
  Jouer avec plusieurs propriétés CSS (`height`, `width` et `display: flex`).
  https://www.alsacreations.com/tuto/lire/1493-css3-flexbox-layout-module.html

- Comment formater le background (la couleur, l'image de fond) ?<br>
  En utilisant CSS : `background` et ses variantes (`background-image: url(...);`, `background-color`, `background-size` et `background-repeat`).

- Comment connaître/comprendre l'imbrication des balises ?<br>
  En l'imaginant comme des poupées russes : qu'est-ce qui contient quoi ?
  Ça se visualiser dans le code en utilisant la touche `TABULATION`

- Comment créer un tableau variable (utilisateur peut ajouter des lignes)?<br>
  On doit passer par JavaScript (créer des éléments dynamiquements avec `document.createElement('<tr>')`, `TRUC.appendChild()` et/ou `TRUC.innerHTML = `<tr>...</tr>`)

- Comment faire un titre modifiable en cliquant dessus<br>
  En ajoutant l'attribut `contenteditable`. Exemple : `<h1 contenteditable>Truc</h1>`.


- est il possible de creer une balise personnalisée nous même ?<br>
  Oui, avec ce qu'on appelle les `Web Components`.

- Comment ne pas se perde en créant une structure HTML avec de nombreux Div dans la première phase de structuration ?<br>
  En utilisant l'indentation/les sauts de ligne/les commentaires, en nommant les choses (avec `class` et `id`).

- Où est-ce qu'on peut lire/écrire des données ?<br>
  Via le service gratuit https://jsonbin.io/. Ça demande à utiliser du JavaScript. Y'a des exemples dans sa documentation https://jsonbin.io/docs/.
  Il y a le service en ligne ; sinon des données réelles d'exemple se trouvent là : https://trello.com/b/IsgEGf0v/gestion-des-articles-du-blog-drawio.json (et la version HTML : https://trello.com/b/IsgEGf0v/gestion-des-articles-du-blog-drawio)

## Les questions et hésitations restées sans réponse (15h25)

- Comment on peut adapter la longeur du liste au nombre des elements?</br>
  Avec `align-items: start` au lieu de `align-items: strech`.
  -

- Est-ce qu'un élément <li> peut être stylysé en CSS avec les même propriété qu'un div ?
  Oui. Ça sert à partager des styles d'affichage. Ou à nommer leur "type".
  
- Peut il contenir en lui meme un div ?<br> 
  
  <ul>
    <li>
      Niveau 1
      
      <ul>
        <li>Niveau 2</li>
      </ul>
      
      <div class="card">
        <header>Nom de la carte</header>
        
        
        <footer></footer>
      </div>
    </li>
  </ul>
  
- Est-ce que vous conseillez plus d'utiliser Flexbox ou Grid Layout ?<br>
  Entre autre https://www.alsacreations.com/article/lire/1794-flexbox-ou-grid-layout.html
- Sur un contenteditable, commment éviter qu'on puisse augmenter à l'infini la taille de la case, et plutôt revenir à la ligne<br>
  
  Utiliser un `textarea`. Peut-être tester avec un `max-width`. Mais y'a des chances que ça gère pas le multiligne.
- Comment faire un menu déroulant ?<br>
  Combiner `display: none` et :hover`+`display: block`.

- Comment espacer les éléments flex de manière fixe ?<br>
  Avec `gap`, exemple `gap: 10px` espace chaque élément de 10px.
  Pour distribuer de manière automatique, sur le conteneur qui _contient_ les éléments flex, lui donner `justify-content: space-between`
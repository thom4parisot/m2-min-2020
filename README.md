# Module MIN 306 • Promo 2020/2021

Module Développement Web (MIN 306) du « [Master innovation &amp; transformation numérique](https://www.sciencespo.fr/ecole-management-innovation/fr/formations/innovation-transformation-numerique.html) »

> La programmation web est un outil puissant et pérenne pour diffuser de l'information, s’exprimer et créer des interfaces interactives.
> Dans ce cours vous aurez une introduction pratique aux notions de programmation pour le web depuis le navigateur jusqu’au serveur.
> Le cours se concentrera sur des standards tels que HTML (structure), CSS (présentation) et JavaScript (interactions, structures de données) ainsi que des concepts sous-jacents (le parcours d'un octet sur le réseau, transit d'un fichier HTML jusqu'au pixel de l'écran, etc.).
> Il sera enseigné sous forme d’atelier à destination d’un public non technique en mettant en œuvre des méthodes agiles.
> Ce cours sera utilisé pour produire et publier le site web de votre data story (MIN302).

L'organisation du cours sera basé sur les apprentissages de la [promotion 2019/2020](https://github.com/oncletom/m2-min-2019) ([lire leur journal de bord](https://github.com/oncletom/m2-min-2019/blob/master/JOURNAL.md)) et de la [promotion 2018/2019](https://github.com/oncletom/m2-min-2018) ([lire leur journal de bord](https://github.com/oncletom/m2-min-2018/blob/master/JOURNAL.md#jeudi-29-novembre)).

**Sommaire**

   * [Journal de bord](#journal-de-bord)
   * [Ressources pour apprendre](#ressources-pour-apprendre)
   * [Ressources pour vos projets](#ressources-pour-vos-projets)
   * [Questions / blocages](#questions--blocages)
   * [Groupes projets](#groupes-projets)
   * [Thématiques de travail au choix](#thématiques-de-travail-au-choix)

# Journal de bord

- 6 janvier 2021 : création des groupes projet, présentation des données (présentiel)
- Vendredi 8 janvier 2021 (toute la journée, présentiel)
- Lundi 18 janvier 2021 (toute la journée, présentiel)
- Vendredi 22 janvier 2021 (toute la journée, présentiel)
- Vendredi 29 janvier 2021 (toute la journée, présentiel)
- Jeudi 4 février 2021 (toute la journée, présentiel)
- Lundi 15 mars 2021 : présentation des rendus

# Ressources pour apprendre

- HTML
  - [Toutes les balises HTML](https://developer.mozilla.org/docs/Web/HTML/Element)
  - [balise `<a>`](https://developer.mozilla.org/docs/Web/HTML/Element/a)
- CSS
  - [Toutes les propriétés CSS](https://developer.mozilla.org/docs/Web/CSS/Reference)
  - [Un jeu avec les sélecteurs CSS](https://flukeout.github.io/)
  - [Transitionner d'un état vers un autre](https://developer.mozilla.org/docs/Web/CSS/transition)
  - [Animer un élément](https://developer.mozilla.org/docs/Web/CSS/animation)
  - [Transformer un élément](https://developer.mozilla.org/docs/Web/CSS/transform) (rotation, inclinaison, perspective 3D)
- DOM (lire et modifier des éléments HTML en écrivant du JavaScript)
  - [Element](https://developer.mozilla.org/docs/Web/API/Element)
  - [document](https://developer.mozilla.org/docs/Web/API/Document)
  - [querySelector()](https://developer.mozilla.org/docs/Web/API/Document/querySelector) et [querySelectorAll()](https://developer.mozilla.org/docs/Web/API/Document/querySelectorAll) pour trouver un ou des éléments dans la page (en utilisant un sélecteur CSS)
- SVG (dessiner des images responsives, stylables et animables en CSS)
  - [https://developer.mozilla.org/docs/Web/SVG](Documentation SVG)
  - [balise `<circle>`](https://developer.mozilla.org/docs/Web/SVG/Element/circle)
  - [balise `<text>`](https://developer.mozilla.org/docs/Web/SVG/Element/text)
  - [Réaliser des icônes en SVG](https://fvsch.com/svg-icons/)
- JavaScript et Node.js
  - [Livre Node.js par la pratique](https://oncletom.io/node.js/#chapitres)
  
# Ressources pour vos projets

- Coordonnées GPS de communes
  - Site laposte
  - [Découpage région/départements/communes](https://geo.api.gouv.fr/decoupage-administratif/regions)
  - [Géolocalisation à partir de Codes INSEE](https://geo.api.gouv.fr/adresse#csv-search)
  - [Fichier Codes INSEE géolocalisés](http://www.nosdonnees.fr/dataset/donnes-gographiques-des-communes-par-code-insee) (peut-être pas à jour)

# Groupes projets

Pas encore constitués.

# Propositions de thématiques/problématiques

## Aides à la presse

- [Classement des titres de presse aidés ](https://www.data.gouv.fr/en/datasets/aides-a-la-presse-classement-des-titres-de-presse-aides/)
- [Compilation des ressources sur les aides à la presse](https://www.data.gouv.fr/en/datasets/aides-a-la-presse-1/)

## Impact environnemental des aliments

- [Détail par ingrédients](https://data.ademe.fr/datasets/agribalyse-detail-ingredient)
- [Site web de démonstration](http://app.agribalyse.fr)

## Historique des changements des conditions générales d'utilisation

Personne ressource : Vincent Viers.

- [Code source](https://github.com/ambanum/CGUs/)
- [Problématiques et enjeux](https://github.com/ambanum/CGUs/wiki/CGUs---Potential-Data-Use-Cases)
- [Dataset](https://github.com/ambanum/CGUs-versions/releases)

## Historique des valeurs de transactions immobilières

- [Demandes de valeurs foncières](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/)
- [Site web de démonstration](https://app.dvf.etalab.gouv.fr/)

## Impact du tourisme

- [Base nationale des données du tourisme](https://www.data.gouv.fr/fr/datasets/datatourisme-la-base-nationale-des-donnees-du-tourisme-en-open-data/)
- Problématiques explorables :
  - Impact du COVID-19 sur l'ouverture des lieux
  - Impact sur la qualité des eaux de baignade
  
## Impacts du changement climatique sur l'eau

- [Piste de départ](https://www.eaufrance.fr/les-impacts-du-changement-climatique-sur-leau)
- Problématiques explorables :
  - Observation de phénomènes extrêmes (températures élevées, températures basses, pluies importantes, pluies absentes) à une échelle locale/compréhensible (ma ville, "mon coin")

## Répartition des parcelles en aides PAC

Personne ressource : Thomas Parisot.

Données confidentielles.

- _Fichier Shapefile_ (`.shp`) contenant l'emplacement des parcelles recevant des aides PAC pour l'agriculture bio, et l'agriculture dite conventionnelle pour un département donné, datées de 2018
- [Site web de démonstration](https://cartobio.org)
- Problématiques explorables :
  - Visualiser les types de cultures, et leur type d'agriculture (bio ou conventionnelle) en fonction de critères (ville, biorégion, etc.)

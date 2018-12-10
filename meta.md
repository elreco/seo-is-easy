# Renseigner la balise meta "title"

Une balise `<title>` indique aux internautes et aux moteurs de recherche le sujet d'une page en particulier. il faut créer un **titre unique pour chaque page de notre site.**
### Bonnes pratiques
- Décrire avec précision le contenu de la page.
- Choisir un titre lisible et évocateur du contenu de la page.
- Eviter les répétitions de mots séparés par une virgule : proposer une vraie phrase, plus incitative au clic pour l'internaute dans les résultats du moteur.
- L’affichage de la balise Title sur Google dépend d’un nombre de pixel, 500 pixels sont disponibles.
- Utiliser des titres brefs, mais descriptifs :

Un titre peut être à la fois court et informatif. Si un titre est trop long ou jugé moins pertinent, Google risque de l'afficher **seulement en partie** ou d'afficher **un titre généré automatiquement** dans le résultat de recherche. Google peut également afficher différents titres en fonction de la requête de l'internaute ou de l'appareil utilisé pour la recherche.

Exemple pour la page d'accueil du site de la formation continue : 

~~~~
<head>
  <title>Centre de formation continue du Cercle digital - Formation Continue Pro</title>
</head>
~~~~

### Sur ModX

Pour renseigner la balise meta "title" sur ModX il suffit de renseigner le champs "Titre long" sur **chacune des pages.** 
>À noter qu'il ne faut pas rajouter le nom du site, il est rebnseigné automatiquement dans le code source sur nos sites

![ModX Meta Title](/img/modx_meta_title.png)

# Renseigner la balise meta "description"

Les balises Meta "description" sont importantes, car Google pourrait les utiliser comme des extraits pour vos pages. Cependant, Google peut choisir d'utiliser une section pertinente du texte visible de notre page si elle correspond à une requête de l'internaute.

### Bonnes pratiques

Rédiger une description capable d'informer et d'intéresser les internautes qui voient notre balise Meta "description" en tant qu'extrait dans un résultat de recherche. Il **n'existe pas de longueur maximale ou minimale** pour le texte contenu dans une balise Meta "description", mais Google nous recommande de faire en sorte qu'il soit suffisamment long pour **figurer entièrement dans la Recherche** (930 pixels): 

![Meta Description](/img/meta_description.png)

(Dans cet exemple ce n'est pas bon car le texte continue)

Voici à quoi ressemble la balise meta "description"

~~~~
<head>
  <title>Centre de formation continue du Cercle digital - Formation Continue Pro</title>
  <meta name="description" content="Le Cercle digital est une marque fédératrice de services dans les domaines de la transition digitale. Une agence éditoriale spécialisée en édition, une agence digitale spécialisée dans les nouvelles technologies, une école supérieure de communication et de journalisme et un centre de formation aux métiers du numérique.">
</head>
~~~~

### Sur ModX

Pour renseigner la balise meta "description" sur ModX il faut remplir le champs "Description" sur **chacune des pages**.

![ModX Meta Description](/img/modx_meta_description.png)

# Outils en ligne

**Tester nos meta** : http://www.referencement.com/simulateur-serp-pixels/

# Pour info : la balise meta "keywords"

Les mots compris dans cette balise sont les mots clés de la page. C'était une balise très utilisée en SEO : les moteurs Altavista et Infoseek le prenait en compte ; il suffisait de mettre les mots clés de la page dans cette balise pour se positionner sur ces mots.

Parce qu'elle a été utilisée de manière trop abusive (remplissage de liste de mots-clés), les moteurs lui ont retiré toute fonction (Altavista en 2002, Yahoo en 2009). Google ne lui aurait même jamais accordé aucune valeur en SEO.

Depuis donc plus de 10 ans les mots qu'elle contient ne sont plus pris en compte pour le référencement, et ceci quel que soit le moteur. A une petite exception près : Yandex, le moteur de recherche russe, serait le seul à analyser les mots de cette balise pour évaluer la pertinence d'une page sur une requête.

Donc, **ça ne sert strictement à rien de la remplir.**

# Pour aller plus loin : balisage de données structurées

*En cours d'écriture, ça ne va pas nous servir pour le moment je pense.*


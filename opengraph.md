# Les balises Open Graph

Le trafic des sites internet est, de nos jours, largement dû aux partages sociaux. Il est ainsi nécessaire de maîtriser cette balise puisqu’elle peut faire une réelle différence sur notre taux de clic.
Imaginons que nous voulions partager un lien sur Facebook et la miniature d’image est la mauvaise qui apparaît, l'Open Graph nous permet d'afficher la bonne.

Ces balises sont faites pour nous offrir **une meilleure expérience utilisateur** et pour **optimiser vos partages.**

# Est-ce que l’Open Graph a un impact sur votre SEO ?

Officiellement, l’Open Graph n’a pas d’impact direct sur notre SEO et il semble qu’il soit seulement là pour optimiser nos liens sociaux.

Cependant, les réseaux sociaux comme Facebook ont gagné une part tellement importante ces dernières années que les moteurs de recherche ne peuvent **plus ignorer les donnés de l’Open Graph dans leurs algorithmes**. 

Il serait difficile de décrire cet impact de manière précise il est sûr qu’il **améliore notre taux de clic** et donc **notre trafic**.

# Comment insérer un Open Graph ?

Pour insérer un Open Graph, il faut :

- ajouter les balises méta dans la balise `<head>` avec les attributs de contenu et de propriété
- spécifier au moins les 4 balises: og:title, og:type, og:url, og:image

D’autres balises existent également si votre page a des objets riches comme des vidéos par exemple.

# Les principales balises OpenGraph

### Les balises obligatoires:

**Og:titre**

C’est le titre de notre page pour l’Open Graph. Il n’y a pas de **recommandations spécifiques** si ce n’est qu'on ne doit pas dépasser les 65 caractères si on ne veut pas que notre titre soit tronqué. Cela marche de **la même façon** pour la [balise méta du titre](meta?id=renseigner-la-balise-meta-quottitlequot) et si Facebook ne trouve pas le og:titre, il utilisera seulement la balise titre.

~~~~
<head>
	<meta property="og:titre" content="Centre de formation continue du Cercle digital - Formation Continue Pro" />
</head>
~~~~

**Og:type**

Cette balise spécifie **le type de notre page** (site web, article, video, musique) et décrit le sujet principal. La liste des possibilités est très longue donc nous pouvons la consulter [ici](http://ogp.me/#types).
~~~~
<head>
	<meta property="og:titre" content="website" />
</head>
~~~~

**Og:image**

C’est l’URL de notre image qui sera affichée dans l’Open Graph. C’est très utile puisque nous pouvons choisir **quelle miniature afficher** et éviter ainsi les visuels qui ne sont pas en rapport avec le contenu de la page.
Habituellement, **une bonne résolution** pour une og image est de 1200 pixels x 627 pixels pour une taille de 5MB.

~~~~
<head>
	<meta property="og:image" content="https://ecole.le-cercle-digital.fr/images/logo.png" />
</head>
~~~~

**Og:url**

C’est l’URL canonique de notre page : simplement l’URL de la page courante.

~~~~
<head>
	<meta property="og:url" content="https://ecole.le-cercle-digital.fr/cursus/supedition/le-concept.html" />
</head>
~~~~

### Les balises non obligatoires :

**Og:description**

C’est le snippet de notre page qui devrait contenir entre 150 et 200 caractères (Facebook peut en afficher jusqu’à 300) et **décrire le contenu** de notre page. Cela marche de la même manière que pour [la balise meta "description"](meta?id=renseigner-la-balise-meta-quotdescriptionquot) mais cela **n’affectera pas notre SEO**.
Je conseille de copier coller la balise meta "description".

~~~~
<head>
	<meta property="og:description" content="Le Cercle digital est une marque fédératrice de services dans les domaines de la transition digitale. Une agence éditoriale spécialisée en édition, une agence digitale spécialisée dans les nouvelles technologies, une école supérieure de communication et de journalisme et un centre de formation aux métiers du numérique." />
</head>
~~~~

**Og:video**
Si nous avons une vidéo sur votre page, c’est ici que vous devrons placer son URL.

~~~~
<head>
	<meta property="og:video" content="https://ecole.le-cercle-digital/presentation.mp4" />
</head>
~~~~

**Og:local**
Cela indique la langue de notre page.

~~~~
<head>
	<meta property="og:local" content="fr_FR" />
</head>
~~~~

**Og:site_name**
C’est le nom de notre site.

~~~~
<head>
	<meta property="og:site_name" content="Le Cercle digital" />
</head>
~~~~


Il existe bien d’autres balises. On peut trouver la liste complète [ici](http://ogp.me/).
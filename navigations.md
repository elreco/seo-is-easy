# Les URL

Google recommande que tous les sites Web utilisent **https://**. Google différencie les versions "www" et "non www" (par exemple, "www.le-cercle-digital.fr" ou "le-cercle-digital.fr"). Lorsque nous ajoutons notre site à la Search Console, Google recommande d'ajouter une version http:// et une version https://, ainsi que les versions "www" et "non www".

L'URL d'un document s'affiche généralement dans un résultat de recherche Google sous le titre du document.

Google mentionne qu'il est judicieux de consacrer du temps à **simplifier autant que possible nos URL**.

Les URL avec des mots pertinents pour le contenu et la structure de notre site sont plus **conviviales** pour les visiteurs qui consultent notre site. 

# Fil d'Ariane

Google recommande d'utiliser [le balisage de données structurées sous la forme de fils d'Ariane](https://developers.google.com/search/docs/data-types/breadcrumbs) lors de l'affichage de ce type de contenu.

# Les liens vers d'autres sites

La réputation de notre site peut être transmise à un autre site vers lequel nous créons un lien. 
Si nous ne voulons pas transmettre **notre réputation à un site**. Il est alors judicieux d'utiliser l'attribut "nofollow".

Utiliser l'attribut "nofollow" comme valeur de l'attribut "rel" d'un lien indique à Google que certains des liens de notre site **ne doivent pas être suivis**, ou que la réputation de notre page ne doit pas être transmise aux pages associées. Pour ne pas suivre un lien, nous devons ajouter l'attribut rel="nofollow" dans la balise d'ancrage du lien, comme indiqué ci-dessous :

~~~~
<a href="http://www.example.com" rel="nofollow">Texte d'ancrage ici</a>
~~~~

# Créer une page de navigation simple

Google recommande de créer une page de navigation simple pour nos sites.

Une page de navigation est **une page simple** de notre site qui affiche la structure de ce dernier et consiste généralement en une liste hiérarchique des pages du site. 

Les visiteurs peuvent consulter cette page s'ils ont du mal à trouver des pages sur notre site. Bien que **les moteurs de recherche consultent également** cette page afin d'obtenir un large champ d'action de l'exploration des pages de notre site, elle sert principalement aux visiteurs humains.
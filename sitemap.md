# Créer un sitemap

La première étape pour que notre **site figure sur Google** est de s'assurer qu'ils puissent le trouver.

# Qu'est-ce qu'un sitemap ?

Un sitemap est un fichier où l'on donne des informations sur les pages, les vidéos et les autres fichiers présents sur notre site.

Les moteurs de recherche lisent ce fichier pour explorer plus intelligemment notre site. Un sitemap indique au robot les fichiers que nous jugeons **importants** sur notre site et fournit également des informations sur ces fichiers : date de dernière mise à jour, fréquence de modification, versions dans d'autres langues...

Le sitemap peut servir à transmettre des informations relatives à des **types de contenu spécifiques** présents sur nos pages, y compris des vidéos et des images. 

Exemple :

- Une entrée de sitemap pour vidéos peut indiquer la durée d'une vidéo, sa catégorie et le public qu'elle cible.

- Une entrée de sitemap pour images peut comprendre des informations sur l'objet, le type et la licence de l'image.

# Est-ce qu'on a besoin d'un sitemap ?

Si les pages de notre site sont correctement reliées entre elles, les robots d'exploration peuvent généralement découvrir la majeure partie de notre site.

Cependant, un sitemap peut améliorer l'exploration de notre site, en particulier dans les cas suivants :

- **Notre site est très volumineux**. Par conséquent, il est plus probable que les robots écartent l'exploration de certaines pages nouvelles ou récemment mises à jour.

- **Notre site comprend de nombreuses pages de contenu mal ou non reliées entre elles**. Si les pages de notre site ne se font pas référence naturellement (il n'y a pas de lien dans le menu, ni sur les pages), on peut les répertorier dans un sitemap pour nous assurer que Google ne les oublient pas.

- Notre site est récent et peu de liens externes permettent d'y accéder. Googlebot et les autres robots explorent le Web en suivant les liens entre les différentes pages. Ainsi, si aucun site ne possède de lien vers nos pages, ils risquent de passer à côté.

> Quoiqu'il arrive Google nous dit que l'utilisation d'un sitemap se révèle généralement utile et ne peut pas nous pénaliser. Je pense qu'il faudrait en créer un pour tous les sites que nous prevoyons de mettre en ligne.

# Quelques outils pour le générer

- https://www.xml-sitemaps.com/ Déjà testé : il faut tout de même vérifier le sitemap après la génération pour le mettre en forme.

- https://support.google.com/webmasters/answer/183668?hl=fr&ref_topic=4581190 Un tuto de google pour le créer manuellement.

# Envoyer notre sitemap à Google

Il existe plusieurs façons de permettre à Google d'accéder à nos sitemaps :

- [L'envoyer à l'aide de l'outil de sitemaps de la Search Console](https://support.google.com/webmasters/answer/7451001)
- Insérez la ligne suivante n'importe où dans notre fichier robots.txt, en indiquant le chemin vers notre sitemap :
Sitemap: http://example.com/emplacement_sitemap.xml
- Utiliser la fonctionnalité "ping" pour demander à Google d'explorer notre sitemap. Envoyer une requête HTTP GET comme ceci :
  http://www.google.com/ping?sitemap=<url_complet_du_sitemap>
Par exemple :
  http://www.google.com/ping?sitemap=https://ecole.le-cercle-digital.fr/sitemap.xml

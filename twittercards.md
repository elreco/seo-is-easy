# Les Twitter Cards

C'est exactement le même principe que pour Open Graph, mais comme son nom l'indique c'est exclusif à Twitter.
Au risque de me répéter, je vous redirige vers la page [Open Graph](opengraph.md) pour comprendre le fonctionnement de ce type de balise.

# Les balises ?

Voici les balises essentielles correspondant aux Twitter Cards.

~~~~
<head>
	<meta name="twitter:card" content="summary_large_image"> <!-- Cette balise est renseignée directement dans le code source -->
	<meta name="twitter:site" content="https://ecole.le-cercle-digital.fr/images/logo.png">
	<meta name="twitter:creator" content="@supedition"> <!-- Cette balise est renseignée directement dans le code source -->
	<meta name="twitter:title" content="Centre de formation continue du Cercle digital - Formation Continue Pro">
	<meta name="twitter:description" content="Le Cercle digital est une marque fédératrice de services dans les domaines de la transition digitale. Une agence éditoriale spécialisée en édition, une agence digitale spécialisée dans les nouvelles technologies, une école supérieure de communication et de journalisme et un centre de formation aux métiers du numérique.">
	<meta name="twitter:image" content="https://ecole.le-cercle-digital.fr/">
</head>
~~~~

# Sur ModX

Sur ModX, ces balises doivent être renseignées de la même manière que pour l'Open Graph : 
>Sur nos sites, certaines balises sont "fusionnées". par exemple lorsqu'on renseigne la balise Open Graph `og:title`, ça remplit automatiquement la balise Twitter Card correspondante `twitter:title`.

![ModX Open Graph](/img/modx_og.png)

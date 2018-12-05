# À quoi sert le fichier robots.txt

Un fichier "robots.txt" indique aux moteurs de recherche les parties de notre site auxquelles ils peuvent accéder et qu'ils peuvent donc explorer. Ce fichier, qui doit être nommé "robots.txt", est placé dans le **répertoire racine de notre site** (c'est une convention). 

!>Il est possible que les pages bloquées par le fichier robots.txt puissent toujours être explorées : pour les pages sensibles, nous devrons utiliser une méthode plus sécurisée.

>Il faudra donc mentionner dans ce fichier des dossiers comme l'espace d'administration par exemple. (Pour ModX : /manager/)

# Comment le créer ?

Il faut donc créer des règles au sein de se fichier avec un format définit. Voici des cas concrets pour mieux comprendre : 

<table>
	<thead>
		<tr>
			<td><b>Définition</b></td>
			<td><b>Code</b></td>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Autoriser l'accès à tout</td>
			<td>
				<pre>User-agent: *
Disallow:</pre>
			</td>
		</tr>
		<tr>
			<td>Désactiver l'indexation d'un dossier spécifique</td>
			<td>
				<pre>User-agent: *
Disallow: /dossier/</pre>
			</td>
		</tr>
		<tr>
			<td>Interdire à Googlebot d'indexer un dossier, sauf pour permettre l'indexation d'un fichier dans ce dossier
			</td>
			<td><pre>User-agent: Googlebot 
Disallow: /folder1/ 
Allow: /folder1/myfile.html</pre></td>
		</tr>
	</tbody>
</table>

Ou passer par un générateur de robots.txt, exemple : 

http://tools.seobook.com/robots-txt/generator/

# Ne pas oublier

Il ne faudra pas oublier de retirer la balise meta "noindex" (si elle existe) qui se trouve dans la balise **head**

~~~~
<head>
  <meta charset="utf-8">
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Centre de formation continue du Cercle digital - Formation Continue Pro</title>
  <meta name="description" content="">
  <meta name="keywords" content="centre de formation continue, Tours, Indre-et-Loire">
  <!-- A RETIRER -->
  <!--<meta name="robots" content="noindex, nofollow">-->
</head>
~~~~


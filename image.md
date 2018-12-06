# Utiliser l'attribut "alt"

Il faut fournir un nom de fichier descriptif et une description de l'attribut "alt" pour les images. L'attribut "alt" nous permet de spécifier un texte de remplacement pour l'image si elle ne peut pas être affichée pour une raison quelconque.

À l'instar de la plupart des autres zones de notre page qui sont ciblées pour l'optimisation, **il est plus judicieux d'utiliser des noms de fichiers et du texte "alt" courts**, mais **descriptifs.**

Exemple : 
~~~~
<img src="/images/gare-de-tours.png" alt="Gare de Tours">
~~~~

### Sur ModX

Sur ModX, chaque image du site comporte un champs personnalisé "Alt Image" que l'on peut remplir depuis le Manager.

![ModX Alt Image](/img/modx_alt_image.png)

# Aider les moteurs de recherche à trouver nos images

Un [sitemap pour images](https://support.google.com/webmasters/answer/178636?hl=fr) fournit à Googlebot plus d'informations sur les images de notre site. 

Celles-ci ont alors **plus de chances d'être présentes** dans les résultats de la recherche d'images. La structure de ce fichier est similaire à celle [du fichier sitemap XML de nos pages Web](sitemap.md).

Il faut ajouter ces informations dans le sitemap que nous avons créé pour les pages Web. 

### Définition des balises d'images

<table>
  <tbody>
    <tr>
      <th><span>Balises</span></th>
      <th><span>Obligatoire</span></th>
      <th><span>Description</span></th>
    </tr>
    <tr>
      <td><code>&lt;image:image&gt;</code></td>
      <td>Oui</td>
      <td>Contient toutes les informations relatives à une seule image. Chaque balise <code>&lt;url&gt;</code> peut contenir jusqu'à 1&nbsp;000&nbsp;balises <code>&lt;image:image&gt;</code>.</td>
    </tr>
    <tr>
      <td><code>&lt;image:loc&gt;</code></td>
      <td>Oui</td>
      <td>URL de l'image
      <p>Dans certains cas, l'URL de l'image peut ne pas se trouver sur le même domaine que notre site principal. Cela ne pose aucun problème, à condition que les deux domaines aient été validés dans la Search&nbsp;Console.</p>
      </td>
    </tr>
    <tr>
      <td><code>&lt;image:caption&gt;</code></td>
      <td>Facultatif</td>
      <td>Légende de l'image</td>
    </tr>
    <tr>
      <td><code>&lt;image:geo_location&gt;</code></td>
      <td>Facultatif</td>
      <td>Emplacement géographique de l'image. Par exemple, <code>&lt;image:geo_location&gt;Limerick, Irlande&lt;/image:geo_location&gt;</code>.</td>
    </tr>
    <tr>
      <td><code>&lt;image:title&gt;</code></td>
      <td>Facultatif</td>
      <td>Titre de l'image</td>
    </tr>
    <tr>
      <td><code>&lt;image:license&gt;</code></td>
      <td>Facultatif</td>
      <td>URL qui renvoie à la licence de l'image</td>
    </tr>
  </tbody>
</table>
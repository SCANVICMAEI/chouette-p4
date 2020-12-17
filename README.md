<h1>La chouette</h1>

![](img/logo.png)

**INTRODUCTION**

<p>Voici mon 3 ème projet demander pour ma formation developpeur web ( chez Open Class Rooms). 
Pour chaque projet un scenario et un cahier des charges m'ait donner</p>

**PRESENTATION DU PROJET**

<p> Employer à la chouette agence on me demande suite au constat de la baisse d'activité de : 

-	Augmenter référencement sur les navigateurs de recherche avec les mots clés « Entreprise web design lyon ».
 
-	Une meilleure accessibilitée du site. 

-	Une analyse de l’état actuelle de votre site. 

-	La mise en place « d’une bonne pratique » pour chaque partie à améliorer 

-	Une augmentation de la vitesse de chargement. 
</p> 

**MISE EN PLACE DES AMELIORATIONS**

**L’accessibilités / Le référencement**

*Problématiques*
- Absence de meta description 
- Présence de keyword
- Contraste faible 
- Le boutons scroll n’ai pas actif
- Les balise « alt » ne sont pas correctement remplie 
- La structure du html n’est pas correcte manque des balises de structure
- La structure des titre (h1 h2 …) n’ai pas correcte 

*Actions*
- Afin de faciliter l’accessibilité j’ai changé la couleur des textes en noir.
- Ajout des étiquettes sur les balises du formulaire
- Modifier les balises <alt> avec un contenue en rapport avec son image.
- Suppressions des liens sur le footer car ils n’avaient pas de chemin. 
- Ajout d’une meta description pour chaque page utilisée en m’appuyant sur les mots clés. 
- La balise <lang> indique la langue utiliser je l’ai donc remplie correctement. 
- Changement du nom de la « page2 » en « contact »
- Ajout des backlinks pour les réseaux sociaux dans le footer (non visible) 
- Chaque balises alt ont été remplies en fonction des photos et images qui l’accompagner 
- J’ai réorganisé les balise titre 

*Bonnes Pratiques*
- Tous les hyperliens doivent être valide afin de simplifier le crawl, et doivent contenir un texte (visible ou non). 
- Afin d’améliorer le référencement de votre site j’ai supprimé les keywords 
- Toutes les balise alt sont des textes alternatifs qui vont être lu par les utilisateurs de lecteurs d’écrans. 
- Il ait important d’avoir un contraste couleur élevé pour une meilleur lecture et compréhension du site (voir les règles WCAG)
- Il est important d’avoir des liens avec un texte descriptif pour les lecteurs d’écran et pour une meilleure compréhension de l’utilisateur. 
- Certains utilisateurs ne peuvent pas utiliser de souris et se servent exclusivement de leur clavier il ait important que le site puisse également être géré via la tabulation. 

- L’ajout d’étiquette de formulaire simplifie la lecture pour les personnes déficientes
- L’utilisations de backlinks en lien avec son contenant favorise un meilleurs positionnement sur les moteurs de recherche . 

*Conclusion* 
- Il serait important de revoir la chartre graphique ainsi que certaine texture et image de fond (texture-paper et lines) afin d’optimiser au mieux l’accessibilité du site.
- Si la suppression des liens du footer ne vous conviennent pas je peux vous proposer une page « partenaire » à ajouter.
- Il serait cohérant de supprimer tout le code non utiliser (style.css bootrstrap.css …) cela ferait gagner en rapidité de chargement et en lisibilité pour vos futur collaborateur développeur ou autres.
- Il serait important également de mettre à jour bootstrap 3, cela engendre des failles de sécurité et rend votre site vulnérable. Pour mettre en place la mise à jour il faudra également changer le CSS et le HTML du site.  


**La vitesse de chargement du site**

*Problématiques*
- Certains dossiers sont trop lourds est mette trop de temps à se charger.
- Le poids des images ralentisse la vitesse de chargement 

*Actions*
- Afin d’alléger le temps de charge pour l’utilisateur j’ai utilisé des CDN (bibliothèque en ligne) pour certains dossier jquery et bootrap. 
 - Les autres dossiers ont été minifier 
- Les <script >sont placer en fin de pages 
- Les images et photos étant trop lourde à charger Je les ai donc compresser via tini.png 
- Certaine image n’était pas à la même taille ce qui rendait un visuel sur certains formats d’écran différents. Certaine ont donc été également redimensionner via resize.imageonline

*Bonne Pratique* 
- Il ait importante de compresser, minifier, ou faire importer par l’utilisateur tous ce qui peux l’être (image, fichier…) de nombreux outils existe (GRIMP, Photos shop, gulp,kraken image Optimizer …)

*Conclusion*
- La mise ne place de cache augmentera la rapidité de chargement de votre site.

**CCL ET REMERCIEMENT**
<p> Un projet interessant qui permet va me permettre d'avoire une approche differentes pour mes autres projets . </p>
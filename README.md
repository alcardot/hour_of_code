# Hour of code - Réalisation d'un site Web  
### Contexte

Accenture organise une initiation au code avec des étudiants de Clermont-Ferrand dans le cadre de l'Hour Of Code.

### Objectifs

Nous vous proposons de réaliser un site web à vos vouleurs en utilisant le langage HTML & CSS ! Ce workshop est destiné aux personnes intéressées par la programmation web. Le but est d'éveiller votre intérêt sur le métier de développeur et de mieux appréhender le monde du numérique. L'objectif n'est pas de faire de vous des développeurs mais de d'apprendre rapidement les fondamentaux et surtout de s'amuser !

## Getting Started

1- Cliquer sur le bouton vert "Clone or download" et sur "Download ZIP" pour récupérer le projet HTML

2- Extraire le zip et stocker le projet sur votre bureau

A l'ouverture du projet on retrouve 3 dossiers : 
- HTML: Contient la page html "index.html" représentant votre page web et les autres fichiers vous servirons à construire les fondations de votre page web.  
- CSS: Contient un fichier style.css déjà pré-rempli (il va assurer la mise en page de votre page web) et toutes les images (background, bannière, icon...)
- Documentation : Un fichier avec la documentation HTML et l'autre pour le CSS. Utiliser impérativement ces documentations tout au long de l'initiation (On y trouve la plupart des réponses du sujet :))

Les liens utiles :
- https://www.w3schools.com/tags/tag_doctype.asp (HTML)
- https://www.w3schools.com/css/ (CSS)

## 2) Votre premier "Hello hour of code" 

Dans le dossier HTML, ouvrir le fichier index.html avec un éditeur de texte disponible sur votre poste (bloc note, notepad++). 

Dans ce fichier, afficher le message "Hello hours of code" dans votre première page web en utilisant la balise suivante
```
<p>text</p>
```
Après avoir enregistré les modifications, faire un clique droit sur le fichier "index.html" dans l'explorateur de fichier puis "ouvrir avec" et sélectionner le navigateur web de votre choix (Internet Explorer, Google Chrome, Mozilla Firefox). Le navigateur doit s'ouvrir et afficher le résultat de votre "Hello hour of code". Si c'est le cas, félicitation vous avez réalisé votre première page web ! Bon c'est pas encore le site de l'année mais patience...

## 3) Reconstitution du squelette d'une page web 

A partir des fichiers "footer.html","header.html" et "body.html" reconstituez la structure type d'une page web en complétant le fichier à l'intérieur de la balise <html> de votre fichier "index.html". Ce dernier contiendra la totalité de votre page web. 

PS: Vous pouvez y supprimer le message "Hello hour of code" qui ne sera plus utile.

Une fois terminé appelez-nous pour valider et passer à la prochaine étape. 

## 4) Exercice de mise en jambe  

#### Dans le header:  

Ajouter un titre à la page (voir documentation HTML) et lier cette page avec le fichier CSS dont le chemin est ../CSS/style.css (voir documentation CSS). Tester en actualisant votre page web (touche F5), vous devez obtenir un début de mis en page avec un fond gris.

#### Dans le body:  

1- Ajouter une image de fond présente dans le dossier CSS au body de votre page web en complétant le fichier style.css (Fait attention à l'extension de l'image choisi : jpg, png, jpeg...)

2- Ajouter une bannière avec une image en fond. 
```
HTML: Ajouter dans l'emplacement prévu pour la bannière la ligne suivante <h1 class="banniere"></h1>. 
Elle représentera votre bannière coté HTML

CSS: Dans le fichier style.css et la class h1.banniere fixer la hauteur de la bannière à 256px et mettre une image avec la propriété "background-image" 
```
3- Faire une barre de navigation  
```
HTML: Utiliser la bonne balise pour faire une barre de navigation avec une liste d'éléments contenant chacun un lien (ex: Acceuil, menu n°1, menu n°2, menu n°3) 

CSS: Compléter la classe menu dans le fichier style.css pour que le menu est une hauteur de 25 px et une couleur de background. Centrer ensuite le texte contenu dans la liste d'élément. Pour finir, changer la couleur du
background lorsque la souris passe sur un item de la barre de navigation (Utiliser la propriété hover dans style.css). 
```
4- Faire deux paragraphes 
```
HTML: En faisant un copier/coller d'un texte fictif (https://www.lipsum.com/) faire un paragraphe avec un titre en <h2> puis un autre paragraphe dans une sous-partie avec un titre en <h3>  

CSS: Utiliser le "padding" pour avoir une belle mis en page (utiliser la classe .contenu), mettre les paragraphes en "justify" et ajouter l'image arrow pour les titres <h2> en ajoutant la ligne suivante:  background: url(arrow.png) no-repeat left bottom;  
```

#### Dans le bas de page (footer) 

```
HTML: Mettre un titre à votre footer en utilisant la balise <p> est en appelant la classe "title_footer" soit <p class="title_footer">. Réaliser ensuite un tableau à une seule ligne contenant 3 liens vers Facebook, Youtube et Twitter. Pour finir, imbriquer une image dans chacun de ces liens pour que ça soit un peu plus sexy 😉 

CSS:  Dans la class "footer" imposer une largeur de 100%, un texte aligner au centre et manipuler la propriété padding: 0 px. N'oublier
pas d'appeler la classe footer dans la balise <table> de votre tableau html soit <table class="footer">. 
 ```
## 5) Réalisation d'une page de connexion 

![alt text](https://github.com/alcardot/hour_of_code/blob/master/Site%20web%20-%20Hour%20of%20code/CSS/page_connexion.PNG)

 ```
HTML:  Utiliser les bonnes balises pour faire un formulaire avec les bons types de saisies ("text","password")

CSS : Essayer de mettre un effet d'ombre sur le cadre du formulaire en utilisant une propriété CSS présente dans la documentation.  (utiliser la class .form dans le fichier style.css) 
 ```
## 6) Atelier Tableau!

#### Exercice n°1: Fair le drapeau de la France (1 ligne et 3 colonnes)

Avec une hauteur de 200 et une largeur de 300 comme ci-dessous. Pour le css utiliser directement dans le html les propriétés présentent dans la documentation CSS (titre : Propriétés CSS pour tableau dans HTML).

![alt text](https://github.com/alcardot/hour_of_code/blob/master/Site%20web%20-%20Hour%20of%20code/CSS/exercice1_tableau.PNG)

#### Exercice n°2: Faire le drapeau des Etats-Unis 

Avec une hauteur de 100 et une largeur de 600 comme ci-dessous.

![alt text](https://github.com/alcardot/hour_of_code/blob/master/Site%20web%20-%20Hour%20of%20code/CSS/exercice2_tableau.PNG)

 

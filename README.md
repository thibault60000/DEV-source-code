# CREAM NG

A full Accessible and Responsiv library [Angular2]

Projet généré par [Angular CLI] version 1.3.1 

** In Developement**


Sommaire
=====================

1. Installation
2. Créer un composant
3. Créer un service
4. Comment build 
5. Tests unitaire
7. Afficher le code HTML/CSS/JS en couleur
8. Crédits 



1. Installation
-------------------

Il est impératif de lancer un `npm-install` pour créer le dossier node_modules.
Lancer avec `ng serve` et ouvrir dans le navigateur à l'URL http://localhost:4200/` .  
Ouverture du navigateur automatique avec `ng serve -o`.

2. Créer un composant 
-------------------

Lancer `ng generate component component name` pour générer un composant.

3. Créer un service
-------------------
Lancer `ng generate component service name` pour générer un composant.

4. Comment build 
-------------------

Lancer `ng build --prod --output-path docs --base-href https://creamng.github.io/Library/` pour build
le projet. Le dossier /docs contiendra le contenu à mettre dans le repo "Library" pour être disponible sur 
la page Git.

De plus, il est nécessaire de copier-coller le fichier "/docs/index.html" et de le renommer en "/docs/404.html" en n'oubliant
pas d'écraser au préalable l'ancien fichier.


5. Tests Unitaire
-------------------

Lancer `ng test` pour executer les tests unitaires (aucun de créer pour le moment)

6. Afficher le code HTML/CSS/TS en couleurs
-------------------

Le seul plugin JS utilisé est prettify.js permettant de structurer le `code` affiché sur la page.
Afficher du code sur la page, nous procédons de la manière suivante : 

```html
<div class="code">
<!--?prettify lang=html linenums=true?--> 
<pre class="prettyprint linenums"> 
<code> 
```

dans lang=html , on peut également avoir css ou javascript( pour les .ts)

Il faut penser à modifier les éléments spéciaux comme ceci : 
```html
{     by   &#123;
}     by   &#125;
<     by   &#x3C;
>     by   &#x3E;
"     by   &#x22;
```
 (les trois derniers peuvent être générer avec "https://mothereff.in/html-entities)"
 
7. Crédits
-------------------

Worldline - 2017 - CreamNG 



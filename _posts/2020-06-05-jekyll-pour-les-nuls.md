---
layout: post
title: Front Matter
categories: ressources memo
author: Julien Doré
tags: ressources memo
datetostring: "5 juin 2020"
---

Un fichier par post dans le répertoire `_posts`.

Chaque fichier va comporter un **Front Matter**: une section du
 fichier au sein de laquelle je vais pouvoir déclarer des variables et leur attribuer une valeur.

 Ainsi :
 
`layout: post` Viendra définir le modele sur lequel la vue sera basée. 
 
`title: Un nouveau titre` En ajoutant cet attribut en front matter. Je remplacerai le titre par défaut attribué par
 le nom du fichier au format : `annee-mois-jour-titre.md`

`date:   1993-01-19 17:07:29 +0200` Idem pour la date. Cet attribut remplace la date par défaut.
 
 `categories: ressources memo` Les catégories définissent un emplacement et son chemin sur la version build. Par d
 éfaut cela définira aussi l'url.  
 
 Il est à noter que je peux choisir d'ajouter des variables supplémentaires prédéfinies telles que `tags:`, `permalink:`... ou encore créer mes propres variables `custom:` 


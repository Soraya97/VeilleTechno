---
title: "Grilles de mises en page"
date: 2020-12-08T17:41:21+01:00
draft: false
categories:
- Conception
tags:
- Maquettes
- UI 
- Design
- Responsive
- Template
- Layout
- Conception
---

[Lien de l'article](https://uxdesign.cc/digging-deep-in-layout-grids-in-mobile-app-design-ef07ace5b291)

![Image for post](https://miro.medium.com/max/2100/1*sBv_YjtE-lebopthC6UiMQ.gif)

## Le nombre optimal de colonnes

Le choix du nombre de colonnes se fait après le positionnement des éléments de base. La grille la plus pratique est sur **12 colonnes**:

- Placement d'un nombre pair ou impair d'éléments facile.
- Toutefois, la largeur est trop petite pour créer des éléments d'une seule colonne.

D'autres grilles sont envisageables:

- Une grille sur 2, 4 ou 8 colonnes peut amener des problèmes de placement d'un nombre pair d'éléments.
- Il est possible d'avoir plusieurs grilles, sans oublier la cohérence.

## Gouttières et marges

- Les marges minimales sur Andorid et iOS sont de 16 pts: il ne faut pas être en-dessous.
- Les gouttières optimales sont de 8 pts.
  - Dans l'idéal, les gouttières sont proportionnelles aux marges.

## Fixité et responsivité

- Utiliser une grille flexible et étirer les colonnes en largeur.
- Garder les mêmes marges, les mêmes gouttières et le même nombre de colonnes.

## Précision de calcul

Si la division de l'écran laisse un reste: 

- Compenser en définissant des marges différentes.
  - Il sera possible d'avoir le nombre de colonnes souhaité.
  - Cela peut poser problèmes aux développeurs.
- Garder la même valeur de marge et utiliser des tailles de colonnes fractionnaires.
  - Avec la densité de pixels, cela ne se remarquera pas.
  - Un éditeur graphique ne permet pas forcément la création d'une telle grille.




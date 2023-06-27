---
title: Image Password Strength
publishDate: 2023-06-27 00:00:05
img: /assets/imagepassword.jpg
img_alt: Image Password Strength
description: |
  concept d'un site web avec une image flou en arrière plan qui devient net en fonction de la longueur du mot de passe
tags:
  - Dev
  - js
  - css
  - html
---
Description :
en arrière plan nous avons image en flou qui devient de plus en plus net en fonction de la longueur du mot de passe, exemple, lorsqu'on tape notre mot de passe au file du temps qu'on le tape le fond devient de plus en plus net.

Caractéristiques clés :

La longueur du texte saisi dans le champ de texte est ensuite calculée en utilisant input.length et assignée à la constante length.

Un calcul est effectué pour déterminer la valeur de flou en fonction de la longueur du mot de passe. Dans ce cas, la valeur maximale de flou est fixée à 20 pixels et elle diminue de 2 pixels pour chaque caractère supplémentaire du mot de passe. Ainsi, plus le mot de passe est long, moins l'effet de flou sera prononcé.

Enfin, la propriété filter de l'élément background est mise à jour en utilisant une chaîne de texte avec la valeur de flou calculée. Cela applique l'effet de flou à l'élément d'arrière-plan.

Technologies utilisées :

Langages de programmation : HTML, CSS, JavaScript

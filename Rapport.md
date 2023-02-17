# Rapport Projet Web 3D

## Auteurs
Maxime LEVIEL & Antoine RECIO ANDRADES

## Organisation du projet

Lors de la mise en place du projet, nous avons choisi une mise en scène simple : une représentation 3D d'une maison d'habitation. Le but des ces modèles est de permettre une visite virtuelle pour de potentiels acheteurs. Etant donné que nous sommes deux sur ce projet, nous avons décidé qu'il serait plus simple de ne pas se partager le travail au début, et d'avancer ensemble en même temps, notamment pendant la période de modélisation initiale. Ensuite, Antoine s'est occupé de faire la transition entre SketchUp et x3dom, puis Maxime a mis en place les différentes fonctionnalités. C'est lors de la première séance de projet que nous décidâmes de la marche à suivre.

## Méthode de réalisation

Vous avons utilisé le logiciel SketchUp pour réaliser le modèle 3D de notre maison. L'avantage d'utilisé ce logiciel est qu'il fut plus aisé de construitre notre modèle de A à Z. Cependant, SketchUp ne propose pas d'export direct vers un fichier x3d. De ce fait, nous avons exporté un fichier VRML depuis SketchUp, et nous l'avons converti en un fichier x3dom en utilisant l'outil AOPT, qui a aussi permis d'optimiser la taille du fichier. Notre modèle était alors exploitable avec x3dom.

## Fonctionnalités à réaliser

Pour simuler une visite de maison, nous avons dû mettre en place un plan. Ainsi, via le biais du plan 2D, il possible de visiter chaque pièce de la maison, simplement en cliquant sur la pièce qu'on souhaite visiter. Nous avons aussi fais en sorte que l'utilisateur puisse obtenir des informations sur le mobilier lorsqu'il clique dessus, s'il souhaite ce les procurer.

## Bilan des résultats

Nous sommes satisfaits du travail rendu, faire la transition entre SketchUp et x3dom fut ardue, à cause de la taille du fichier résultat. Au départ, nous passions par BS Contact pour convertir le VRML en x3dom, mais le fichier résultant était bien trop gros pour charger sur la page web (Presque 1 millions de ligne de code !). Heureusement, AOPT nous a permis de trouver une solution à ce problème. Une frustration dans ce projet a été l'impossibilité d'utiliser le mode "Walk" dans notre scène. Lorsqu'on s'y essaye, la caméra change d'angle à 90 degrés, et impossible de la remettre dans le bon sens. 
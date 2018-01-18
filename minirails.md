# Minirails

Le projet minirails constitue un sous ensemble de miniville

# Synopsis
## Miniville
Miniville est un projet de création d'une miniville connecté contenant :
* des décors 2D ou 3D
* des feux de signalisations synchronisé et eventuellement connectés
* une route représenté par des lignes sur papier
* des voitures capable de suivre ces lignes et de respecter les feux
Peu a peu je souhaitais que l'on ajoute de l'intelligence à ces voitures afin qu'elle interagisse entre elle. 

## Minirails

Le problème de miniville c'est que la pente avant de commencer la réalisation est un peu forte pour des débutants. Je souhaite un projet avec une progression plus réguliere et des réalisations assez tôt dans le projet. J'ai donc choisi comme premiere phase minirails. 

Minirail est un chemin de fer(PLA) connecté contenant :
* des décors 2D ou 3D
* des feux de signalisation synchro et optionnellement connecté
* des monorails servant de guide
* des locomotives connectées
* un système de centrale de commande
* des aiguillages
* des points de recharges

## Pourquoi
Ce projet me semble un bon début car j'ai un peu d'experience dans la modelisation/impression 3D et une vision plus claire des éléments necessaires à la réalisation que pour miniville. Soyons franc cela me permet de ne pas trop m'éloigner de ma zone de confort.

# Méthode de travail
Il y a déjà 3 participants(sans me compter) qui ont contribué au projet minirails. Cela s'est fait naturellement. En apportant des idées, des objections, des exemples concrets d'application. 
Travailler tous ensemble sur les points cruciaux et se repartir les taches répétitive dans un premier temps et nous modifierons la structure si besoin de façon collégiale.

# Etapes

## Conception matériel

* jonctions
* rails droits
* rails courbes
* aiguillage
* chassis fonctionnel dans les deux directions

## Conception électronique

* conception module d'adressage attiny pour réseau i2c(exemple aiguillage, signalisation, ...).

* Gestion du réseau i2c et de l'interface de controle via esp32
* Conception véhicule 
** camera pilotable pour le streaming
** commandes : avant/arriere/start/stop




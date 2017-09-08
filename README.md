#Bienvenue à Miniville

## Description

L'idée est de produire une miniville interactive. Ce qui m'intéresse c'est surtout la route et la circulation mais avoir des maisons et commerces en plus peut être sympa. 
Ce projet impliquera de la conception 2D/3D, de l'électronique, de l'urbanisme et de la programmation. La réalisation devra être accessible à des enfants, contenir peu d'intelligence au début et évoluer de maniere iterative. Les éléments qui composent la ville devront être interdépendant(indépendant mais capable d'entrer en interaction) et interchangeable.

## Composition :

1. Voitures suiveuse de lignes et capable de s'arreter au feu rouge.
1. Lignes noires au feutre sur des feuilles A4 ou A3.
1. feux de signalisation route
1. feux pour pieton synchronisé avec les feux de routes.
1. bouton pour forcer le feu rouge route.

### composition optionnelle

1. garage de communication avec les voitures
1. maisons
1. commerces
1. Végétation
1. ...

## Pistes

* J'ai reperé quelques super montages de voiture suiveuse de ligne. Elle sont de la taille d'une petite boite d'allumette, facile à construire et peu couteuse(5à 10€ l'unité)
  1. http://www.ostan.cz/PocketBot2/
  1. http://www.instructables.com/id/How-to-make-worlds-smallest-line-follower-robot-ro/
  1. http://www.instructables.com/id/ATtiny13A-Line-Follower/

## formes du projet

Je souhaite réaliser ce projet 3 fois. Une fois dans une salle bien équipé avec un gros budget. Une fois avec un budget limité et une fois en mode recyclage.

## axes de réflexion

Que peut on apprendre via ce projet?
  * Fonctionnement et utilisation des composants de bases : résistance, led, transistor, condensateur.
  * Conception et , miniaturisation via circuits intégré ou mini micro contrôleurs.
  * Montages électroniques de base : brachement d'un moteur, d'un servo-moteur, leds, capteurs.
  * Se documenter : En lisant les spec matériel ou en s'inspirant de montage existant.
  * Impressions de circuit imprimé, de décor, de chassis de voiture, de structure de batiment via CNC.
  * Impressions complémentaires de la CNC via imprimante 3D.
  * Réflexion autour de la conception des éléments de base (voiture, route, signalisation)
    * Gestion de l'énergie, comment alimenter les feux, les voitures.
    * Comment gerer la synchronisation des feux?
    * Comment gerer les interactions entre les voitures?
    * Comment fixer les feux à la route. Je rappel quee la route est éphémère. C'est une feuille de papier avec des lignes au marqueur.
    * Comment associer les plaques de routes(Cela dépend bcp de la gestion de l'énergie et de la synchronisation)
  * Programmation de micro controlleurs.
  * Recyclage de matériel existant : reprogramation de microcontroleur ou assemblage via relai, optocoupleur etc...

  On peut aller plus loin et faire une maquette de bison futé(utilisation de l'induction pour determiner le traffic). Cela peut permettre de boucler sur le data streaming, l'analyse de donnée et la data visualisation...  Je pense que ce projet peut intéresser tt le monde.

## Par où commencer?

Je souhaite que le projet soit itératif et que l'on ai rapidement quelque chose qui fonctionne à chaque itération.
C'est pour cela que je donne une piste pour commencer, je n'impose rien.

1. feu tricolore de signalisation
1. comportement du feu tricolore
1. ajout feu piéton
1. gestion d'interruption


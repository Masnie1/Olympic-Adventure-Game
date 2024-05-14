## Documentation

## Scenario du jeu

Initialement, notre jeu devait présenter une course entre deux personnages, où le joueur contrôlait l'un d'eux, tentant de fuir l'autre pour protéger sa flamme olympique. L'objectif était de maintenir la flamme intacte le plus longtemps possible pour accumuler des points, avec la menace constante d'être capturé par l'adversaire, ce qui réinitialisera la partie. Cependant, en raison de difficultés techniques rencontrées lors de l'implémentation de cet adversaire, le scénario du jeu a évolué vers un autre jeu.
Dans la version finale du jeu, le joueur se retrouve seul sur un circuit de course. Le défi est de compléter le parcours aussi rapidement que possible, tout en gérant son endurance. Le gameplay s'articule autour de la navigation via souris et clavier, avec le joueur qui doit suivre le tracé du parcours pour avancer. À chaque fin de course, le temps réalisé est comparé au précédent record. Si le joueur bat son meilleur temps, ce nouveau record est sauvegardé et affiché ; sinon, il a la possibilité de retenter sa chance autant de fois qu'il le souhaite pour améliorer sa performance.

# les Contrôles du Porteur de la flamme Olympique

* Z pour avancer (ou Q en clavier QWERTY)
* S pour reculer
* Maintient du clic gauche pour tourner la caméra et le personnages
* Maj (Shift) pour accélérer le personnages (cela consomme de l'endurance)

# Menu du jeu 

Le menu se compose uniquement du bouton Play pour être amené dans le jeu :

<img src="https://imgur.com/a/MVffFtd" alt= “” width="70%">

# Jeu

Dans notre jeu, il y a une ligne de départ, pour commencer le chronomètre de la course, et une ligne d'arrivée pour finir la course et stopper le chronomètre pour établir le temps à battre.

Ligne de départ :

<img src="https://imgur.com/a/KGMjoHF" alt= “” width="70%">

Ligne d'arrivée :

<img src="https://imgur.com/a/5oaCV84" alt= “” width="70%">


# Mécanique

- L'endurance (situé en haut à droite de l'écran) est la ressource du porteur, qui se recharge sur le temps, pour accélérer avec le bouton Shift mais on ne pourras plus courir pendant quelques instant lorsque celle-ci est totalement épuisé par le joueur.
<img src="https://imgur.com/a/y9FHCuC" alt= “” width="70%">

- Ligne de départ est un déclencheur permettant d'éffacer le temps actuel et de relancer le chronomètre.
- Ligne d'arrivée est un déclencheur permettant d'arreter le chronomètre et de remplacer le meilleur temps si il est meilleur.
<img src="https://imgur.com/a/F9FIStj" alt= “” width="70%">
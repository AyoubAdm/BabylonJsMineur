# Tank Battle Game

Ce projet est une amélioration d'un jeu de bataille de chars. Vous contrôlez un char et devez combattre des zombies et un boss zombie.

## Ajouts et améliorations

### Esthétique
- Ajout d'un modèle 3D de char
- Ajout d'un modèle 3D de zombie
- Changement de la texture du sol

### Fonctionnalités
- Ajout d'atouts qui apparaissent toutes les x secondes et qu'on peut récupérer en roulant dessus. Il y a 3 types d'atouts :
  - `fireRateUp` : augmente la cadence de tir des boulets de canon du char
  - `speedUp` : augmente la vitesse de déplacement du char
  - `cannonBallUp` : augmente le diamètre et la vitesse des boulets de canon
- Ajout d'un zombie boss (non tuable pour l'instant) qui invoque des "dudes" toutes les x secondes.

###Résolution bugs
-Les boulets de canon ne travers plus plusieurs dude à la fois.

## Comment jouer
- Clonez ou téléchargez le dépôt
- Ouvrez le fichier `index.html` dans un navigateur web compatible avec WebGL
- Utilisez les touches fléchées ou zqsd pour déplacer le char
- Appuyez sur la barre d'espace pour tirer des boulets de canon
- Appuyez sur la touche L pour tirer un laser
- Récupérez les atouts pour améliorer votre char et combattez les zombies et le boss zombie

## À venir
- Ajout de la possibilité de tuer le boss zombie
- Améliorations des graphismes et des effets sonores
- Ajout de niveaux supplémentaires et de différents types d'ennemis

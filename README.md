# cub3D

**cub3D** est un projet de jeu 3D développé dans le cadre de la formation à l'école 42. Ce projet implémente un moteur de jeu en 3D à la première personne en utilisant **MLX** pour l'affichage graphique et **raycasting** pour le rendu de l'environnement en 3D.

## 🚀 Technologies utilisées

- **MLX** : Bibliothèque graphique pour la gestion des fenêtres, l'affichage des images et des pixels, utilisée pour dessiner l'environnement 3D.
- **C** : Langage principal utilisé pour le développement du projet.
- **Raycasting** : Technique de rendu utilisée pour simuler une vue en 3D dans un environnement 2D.
- **Makefile** : Automatisation de la compilation du projet.

## 🎮 Fonctionnalités

- **Rendu 3D à la première personne** : Simulation d'une vue 3D à partir d'une carte 2D grâce au raycasting.
- **Déplacement du joueur** : Le joueur peut se déplacer, tourner et interagir avec l'environnement à l'aide des touches du clavier.
- **Gestion de la carte** : La carte est représentée par un tableau 2D où chaque cellule est un mur ou un espace vide.
- **Affichage de l'environnement** : Les murs sont rendus en perspective en fonction de la distance du joueur et de l'orientation de la caméra.

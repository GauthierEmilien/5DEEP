# Projet 5DEEP

Antoine Franc
Emilien Gauthier
Aymeric Nosjean
Dorian Maliszewski
Frederic Malphat

## Installation

- Télécharger le jeu de données d'entrainement ainsi que le jeu de test sur canvas
- Déplacer les fichiers télécharger à la racine du projet
- L'arborescence du projet doit être la suivante :
  - histories/
  - images/
  - tuner/
  - weights/
  - **seg_test**/
    - buildings/
    - street/
    - ...
  - **seg_train**/
    - sea/
    - glacier/
    - ...
  - 5DEEP.ipynb
  - Tuner.ipynb


## Quelques précisions

Les modèles sont sauvegardés dans le dossier **weights**.

L'historique des entrainements de chaque modèle est sauvegardé dans le dossier **histories**.
Ils permettent de ne pas avoir à relancer l'entrainement du modèle pour avoir le graphique.

Tous les entrainement des modèles ont été accélérés grâce à la carte graphique NVIDIA.

Si le dossier **tuner** est supprimé, en relançant le fichier tuner.ipynb, le processus de recherche des meilleurs hyperparamètre sera relancé. Ce processus à pris plus de 2h pour nous avec la carte graphique.
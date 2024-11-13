# Projet Reinforcement Learning - Frozen Lake

## Description du projet
Ce projet utilise le **Reinforcement Learning** et plus spécifiquement l'algorithme de **Q-Learning** pour résoudre le problème de navigation dans un environnement "Frozen Lake" (Lac Gelé). L'objectif est de guider un agent pour qu'il atteigne un objectif dans un environnement semé d'obstacles en maximisant les récompenses et en minimisant les risques.

## Structure des fichiers
- `notebook.ipynb`: Le notebook Jupyter où est implémenté l'algorithme de Q-Learning.
- `Rapport_Finale_Reinforcement_learning.pdf`: Un rapport détaillé expliquant les étapes du projet, la méthodologie, les résultats et les conclusions.
- `README.md`: Ce fichier, fournissant une vue d'ensemble du projet.

## Méthodologie
L'agent est entraîné avec une approche Q-learning dans un environnement avec différentes cases représentant :
- **S** : Point de départ
- **F** : Surfaces traversables
- **H** : Trous (zones dangereuses)
- **W** : mûr
- **P** : Power-up
- **T** : Trap (piège) 
- **G** : Objectif final

Les paramètres comme le taux d'exploration (epsilon), le taux d'apprentissage (alpha), et le facteur de réduction (gamma) ont été ajustés pour optimiser les performances de l'agent.

## Résultats
Après plusieurs itérations d'apprentissage, l'agent a appris à éviter les obstacles et à atteindre systématiquement l'objectif.

## Auteurs
- Razafindrakoto Tsiba
- Sow Oumou

## Références
- Documentation sur Frozen Lake : https://www.gymlibrary.dev/environments/toy_text/frozen_lake/
- Sutton, R. S. (2018). *Reinforcement learning: An introduction*.

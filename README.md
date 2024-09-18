# Projet d'Analyse Financière - Prévision de Churn des Clients

## **Objectif **
L'objectif de ce projet est de prédire le départ (churn) des clients d'une banque avant que cela ne se produise. Pour cela, une analyse des données des clients est réalisée, suivie d'un entraînement de plusieurs modèles de machine learning pour optimiser les prédictions.

## Contenu du projet
Le projet se compose des étapes suivantes :
1. **Étude des données** : Exploration des données clients de la banque afin d'identifier les caractéristiques pertinentes.
2. **Prétraitement des données** : Nettoyage et transformation des données pour les préparer à l'entraînement des modèles.
3. **Réduction de dimension** : Utilisation de la méthode PCA pour réduire le nombre de dimensions.
4. **Recherche d'hyperparamètres** : Optimisation des modèles à l'aide d'une recherche par grille (Grid Search).
5. **Modèles de prédiction** : Entraînement de plusieurs modèles (Bagging, RandomForest, Boosting) pour identifier celui offrant les meilleures performances.

## ** Prérequis **
Avant de lancer le projet, assurez-vous d'avoir installé les bibliothèques suivantes dans votre environnement Colab ou local :
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## ** Exécution du projet **
1. Importer le notebook sur [Google Colaboratory](https://colab.research.google.com/).
2. Exécuter les cellules dans l'ordre pour charger les données, les analyser, et entraîner les modèles.
3. Visualiser les résultats et les métriques de validation croisée pour évaluer la performance des différents modèles.

## **Jeu de données**
Le jeu de données utilisé est celui des clients d'une banque, contenant des informations telles que l'âge, le genre, le nombre de comptes dépendants, et plusieurs autres variables financières.

## **Résultats attendus**
L'objectif final est de développer un modèle capable de prédire avec précision quels clients sont susceptibles de quitter la banque, permettant ainsi de mettre en place des actions préventives.

## **Auteur**
Hakima Djermouni


# P24_IF29_GR02

### Introduction du projet

Ce projet présente le travail effectué par le groupe 2 pour le projet de l’UE IF29 - Traitement de données (Data Analytics). L’objectif de ce projet est d’implémenter sur un même dataset et pour une même problématique une approche non supervisée et une approche supervisée et d’en faire le comparatif de Machine learning.

L'objectif est de mettre en œuvre une méthode non supervisée et une méthode supervisée pour le même problème sur le même ensemble de données et de les comparer.

Nous mettrons en œuvre deux algorithmes d'apprentissage automatique pour détecter les profils Twitter "suspects". Une étude comparative sera ensuite menée sur les résultats fournis par chacun des deux algorithmes sur les dimensions pertinentes. Ensuite, nous effectuons une optimisation améliorée.

Ce repository contient l'ensemble des ressources qui ont été utiles à la réalisation du projet d'IF29 nécessitant l'implémentation de deux méthodes de machine learning (supervisé et non supervisé) afin de trouver des profils twitter dit suspect.

---

### Introduction au fichier de codes

1. Le répertoire `Traitement_des_donnees` contient trois fichiers qui sont utilisés pour préparer les données：

   - `Traitement_des_donnees/1_create.ipynb` qui nous a permis d'importer les données dans mongo_DB

   - `Traitement_des_donnees/2_feature_extaction.ipynb` qui nous a permis de réaliser le groupement par user et la selection des attributs pour le calcul de nos dimensions

   - `Traitement_des_donnees/3_features_cacl.ipynb `qui nous a permis de réaliser les calculs permettant d'obtenir nos dimensions pour le petit dataset sur mongo db

2. `pca_explorer.ipynb` Le fichier pca_explorer.ipynb est utilisé pour déterminer si l'ensemble de données doit être réduit à l'aide de l'ACP et à quelles dimensions.

3. Le code pour l'apprentissage automatique se trouve dans le répertoire `SVM`, `K-Means` respectivement

   - `SVM/ML_SVM.ipynb` qui permet d'exécuter notre algorithme SVM


   - `K-Means/Kmeans_avec_pca.ipynb` qui est le fichier dans lequel se trouve l'intégralité du code nécessaire pour exécuter notre K-Means avec PCA 


   - `K-Means/Kmeans_sans_pca.ipynb` qui est le fichier dans lequel se trouve l'intégralité du code nécessaire pour exécuter notre K-Means sans PCA 

# MEA-optimisation-project
Estimation de paramètre d'une regression linéaire pénalisée (LASSO) via un problème de minimisation :
Ce projet implémente l'algorithme **FISTA (Fast Iterative Shrinkage-Thresholding Algorithm)** pour résoudre un problème de régression LASSO sur un jeu de données de **partage de vélos (Bike Sharing Dataset)**.

Le notebook Python contient :

- L'implémentation de l'algorithme **FISTA** pour la minimisation d'une fonction convexe avec régularisation L1.
- L'implémentation de l'algorithme **PEACEMAN-RACHFORD** pour la minimisation d'une fonction convexe avec régularisation L1.
- Une illustration de la convergence de la solution `x_n` sur plusieurs itérations.
- La prédiction du nombre de locations de vélos (`Y_pred`) à partir des données `Xtilde`.
- Des visualisations graphiques pour analyser les performances.

**Base de données utilisée :**  
Le projet utilise le jeu de données **Bike Sharing Dataset**, qui contient des informations journalières sur le nombre de locations de vélos ainsi que des variables explicatives telles que la météo, le jour de la semaine et d’autres facteurs influençant la demande. On ne se concentre que sur la météo.

---

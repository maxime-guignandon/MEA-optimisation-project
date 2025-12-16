# Projet – Régression LASSO avec FISTA, Peaceman–Rachford et ADAM

Ce projet étudie la résolution d’un problème de régression LASSO appliqué au dataset Bike Sharing (prédiction du nombre de locations de vélos).
L’objectif est de comparer plusieurs algorithmes d’optimisation pour estimer les coefficients d’un modèle linéaire régularisé.

**Contenu du notebook :**

1) Formulation du problème

-Régression LASSO : minimisation d’un terme de moindres carrés avec pénalisation L1

-Vérification des hypothèses (convexité, différentiabilité, existence de solutions).

2) Algorithms implémentés

-FISTA : méthode de gradient proximal accélérée.

-Peaceman–Rachford (PR) : méthode de splitting, qui s’avère la plus performante dans ce projet.

-ADAM : utilisé pour comparaison, convergence moins satisfaisante dans ce contexte.

3) Analyse de convergence

-Étude de la loss par algorithme.

-Influence du pas (τ) et des hyperparamètres.

-Comparaison des temps d’exécution et de la stabilité numérique.

4) Sélection du meilleur λ

-Recherche du paramètre de régularisation optimal via PR.

-Analyse de la sparsité et du compromis biais/variance.

5) Évaluation finale

-Prédiction du modèle LASSO obtenu.

-Visualisation 

-Calcul du R^2.

-Discussion sur les limites du modèle linéaire par rapport à la non-linéarité des données.


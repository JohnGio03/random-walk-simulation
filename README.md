# random-walk-simulation
Simulation de marches aléatoires en Python

# Description du projet
Ce projet illustre le comportement d’une marche aléatoire simple (Random Walk) en une dimension.
À chaque étape, la position évolue de +1 ou –1 avec probabilité égale.

Ce type de processus est fondamental en :

probabilités

statistiques

physique (mouvement brownien)

finance (modélisation des prix)

IA (exploration aléatoire)

L’objectif est de simuler plusieurs marches, de les visualiser et d’analyser leurs propriétés mathématiques

# Objectifs pédagogiques
Comprendre le comportement d’une marche aléatoire

Illustrer la loi des grands nombres

Montrer que la variance croît comme √n

Visualiser plusieurs trajectoires

Analyser la dispersion et la convergence

Relier simulation numérique et théorie mathématique


# Contenu Notebook
Génération d’une marche aléatoire :
Utilisation de numpy pour simuler des pas +1 / –1.

Visualisation de plusieurs marches :
Graphiques réalisés avec matplotlib.

Analyse statistique :
positions finales
moyenne
variance
comparaison avec les valeurs théoriques

Vérification expérimentale :
convergence de la moyenne vers 0
croissance de l’écart-type en √n


# Rappels mathématiques

Pour une marche aléatoire simple :

Xi = +1 ou -1 avec probabilité 1/2

E[Xi] = 0

Var(Xi) = 1

Somme des pas :

        Sn = X1 + .... + Xn

Loi des grands nombres :

      Sn/n ---> 0

La moyenne des positions converge vers 0.

Variance : 

   Var(Sn) = n

Ecart-type :

    𝜎(Sn) = √n

La marche s’éloigne du point de départ, mais lentement, proportionnellement à √n.

# Technologies utilisées

Python

NumPy

Matplotlib

Jupyter Notebook


# Pistes d’amélioration

Marche aléatoire biaisée

Marche en 2 dimensions

Barrières absorbantes / réfléchissantes

Distribution empirique des positions

Comparaison avec une loi normale

Simulation d’un mouvement brownien


# Compétences développées

Simulation numérique

Probabilités et processus stochastiques

Visualisation scientifique

Analyse statistique

Rédaction d’un projet mathématique

Organisation d’un projet sur GitHub









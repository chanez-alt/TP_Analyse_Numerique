# Résolution d'une équation non linéaire
# Sommaire :
 - [Introduction](#introduction)
 - [Méthode dichotomie](#méthode-dichotomie)
 - [Méthode du point fixe](#Méthode-du-point-fixe)

## Introduction 
> Dans ce TP on va étudier des différents méthodes des résolutions d'une équation non linéaire.
## Méthode dichotomie
> La méthode de dichotomie ou méthode de la bissection est, en mathématiques, un algorithme de recherche d'un zéro d'une fonction qui consiste à répéter des partages d’un intervalle en deux parties puis à sélectionner le sous-intervalle dans lequel existe un zéro de la fonction.

<p align="center"><img  src="méthode de dichotomie.png"/></p>.

> + 1) Avantages de la méthode de la dichotomie :

    -simple
    -vitesse de convergence constante
    -On peut calculer nombre d'itérations facilement si on connait epsilon.
    -L’erreur dans la methode de la dichotomie ne depend pas de f.

> + 2) Inconvénients de la méthode de la dichotomie :

    - lente
    - nécessite f (a) × f (b) < 0
    - nécessite la continuité
    
## Méthode du point fixe 
>La méthode du point fixe appliquée à la résolutions d’équations non linéaires
consiste à élaborer un schéma itératif, en l’occurence une suite convergente vers un point fixe x d’une certaine application g, ce point fixe est en l’occurence
la solution de l’équation f(x)=0.
L’objectif ce méthode est la résolution d’équation du type :
<p float="left">
  <img src="méthodepointfixe.PNG" width="250" />
  <img src="Fixed_point_example.PNG" width="250" /> 
</p>

> + 1) Avantages de la méthode point fixe : 
    -Ne demande pas le calcule de f'.
> + 2) Inconvénients de la méthode point fixe :
    -Choix de g de manière algébrique



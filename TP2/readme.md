# TP2 :Interpolation polynomiale
# Sommaire :
 - [Introduction](#introduction)
 - [Formule de Lagrange](Formule-de-Lagrange)
 - [Formule de Newton](Formule-de-Newton)
 - [Conclusion](#conclusion)
## Introduction
> En analyse numérique, l’interpolation polynômiale est une technique d’interpolation d’une fonction par un polynôme. Etant donnés une fonction f : [a, b] -> R et N > 1 un entier naturel. Soint x0, x1, · · · , xN (N + 1) points (appelés aussi des noeuds) deux à deux distincts dans [a, b]. Le but est de chercher à trouver un polynôme p (à coefficients réels) vérifiant le système suivant :  
<p align="center"><img  src="interpolation.PNG"/></p>

    -Il existe un unique polynome p vérifiant le systéme précedent.
## Formule de Lagrange

>L’unique polynôme vérifiant le systéme précedent, appelé le polynôme d’interpolation de Lagrange, s’écrit sous la forme suivante :
<p align="center"><img  src="Formule de Lagrange.PNG"/></p>
On a les propriètés suivantes :
<p align="center"><img  src=imagelagrange.PNG/></p>
- Li (x) est un polynôme de degré égal (exactement) à N.

> *  Exemple :
 <p align="center"><img  src="fonction.PNG"/></p>
La répresentation graphique de la fonction :
<p align="center"><img  src=imagelagrange2.PNG/></p>
L'application de la formule de lagrange : 
<p align="center"><img  src=imagelagrange3.PNG/></p>

> * Interpolation Equidistante :
<p align="center"><img  src=interpolationequidistance.PNG/></p>

> * Interpolation Tchebycheff: 
<p align="center"><img  src=interpolaationtchebycheff.PNG/></p>

## Formule de Newton
> l’alternative de Newton (ou méthode des différences divisées). Cette méthode ne diffère de l’interpolation lagrangienne que par la façon dont le polynôme est calculé, le polynôme d’interpolation qui en résulte est le même. Pour cette raison, on parle aussi plutôt de la forme de Newton du polynôme de Lagrange. Le polynôme d’interpolation de Newton associé à la fonction f aux noeuds x0, x1, · · · , xN s’écrit comme suit :
<p align="center"><img  src=formulenewton.PNG/></p>
L'application de la formule de Newton : 
<p float="left">
  <img src=tableaunewton.PNG width="250" />
  <img src=grapheformulenewton.PNG width="250" /> 
</p>

## Conclusion
> En analyse numérique (et dans son application algorithmique discrète pour le calcul numérique), l'interpolation est une opération mathématique permettant de remplacer une courbe ou une fonction par une autre courbe (ou fonction) plus simple, mais qui coïncide avec la première en un nombre fini de points (ou de valeurs) donnés au départ. Suivant le type d'interpolation, outre le fait de coïncider en un nombre fini de points ou de valeurs, il peut aussi être demandé à la courbe ou à la fonction construite de vérifier des propriétés supplémentaires. Le choix des points (ou valeurs) de départ est un élément important dans l'intérêt de la construction.

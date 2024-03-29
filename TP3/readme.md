# PROJET ANALYSE NUMERIQUE
# Intégration Numérique
# Sommaire :
 - [Introduction](#introduction)
 - [Méthode des réctangles](#Méthode-des-réctangles)
 - [Méthode du point milieu](#Méthode-du-point-milieu)
 - [Méthode des trapèzes](Méthode-des-trapèzes)
 - [Méthode de Simpson](#Méthode-de-Simpson)
 - [Mini projet](#Mini-projet)
 - [Conclusion](#conclusion)
## Introduction
> L'intégration est un des problèmes les plus importants que l'on rencontre en analyse. En effet, on rencontre souvent des intégrales dont le calcul par des méthodes analytiques est trés compliqué ou meme impossible, car il n'existe pas d'expression analytique d'une primitive de la fonction à intégrer.
    
> Dans ces cas, on peut appliquer des méthodes composites pour evaluer la valeur de l'integrale
donnée.
> On appelle formule composite l’expression caractérisant cette estimation.
Notons k l’indice des n sous-intervalles, h = (b − a)/n la longueur de chacun d’eux, xk = a + kh la borne inférieure et
mk = a + (k + 1/2)h le point milieu, ceci pour k entre 0 et n − 1.Voici quelques formules composites :
- Méthode des réctangles :
<p align="center"><img src="image1.PNG"/></p>

- Méthode du point milieu :
<p align="center"><img src="image2.PNG"/></p>

- Méthode des trapèzes :
<p align="center"><img src="image3.PNG"/></p>

- Méthode de Simpson :
<p align="center"><img src="image4.PNG"/></p>

> soit les 4 fonctions suivantes :
<p align="center"><img src="image5.PNG"/></p>
           
    - Le but de ceTP est de comparer ces 4 méthode d’intégrations numériques.
## Méthode des rectangles à gauche :
> La plupart des méthodes d'intégration numérique fonctionnent sur le même principe. On commence par couper le gros intervalle [a,b] en N plus petits intervalles [ai,ai+1], avec a1=a et aN+1=b. Puis, pour chaque intervalle [ai,ai+1], on essaie d'approcher . Les moyens les plus simples sont :
la méthode des rectangles à gauche : on approche  par . Géométriquement, cela signifie qu'on approche l'intégrale de f par l'aire des rectangles hachurés en vert :

<p align="center"><img src="image6.png"/></p>
<p align="center"><img src="demorectangle1.gif"/></p>

## Méthode du point milieu

> la méthode du point milieu : 
<p align="center"><img src="image8.png"/></p>
<p align="center"><img src=demopointmilieu.gif/></p>
   
    -simulation de ces deux méthodes :
<p align="center"><img src=comparison.gif/></p>
##  Méthode des trapèzes : 

>La méthode d'intégration approchée, dite des trapèzes, décrite ci-après, introduite par Newton & Cotes est plus précise que la méthode élémentaire, dite des rectangles, correspondant aux sommes de Cauchy-Riemann, consistant à remplacer la fonction initiale par une approximation en escalier. Graphiquement, sur l'intervalle [xi, xi+1], on remplace l'arc de courbe par le segment [MiNi+1], donc l'aire sous la courbe, par le « rectangle » xi Mi Ni+1 xi+1 (figure de gauche) :
<p align="center"><img src="image9.jpg"/><p>

>La méthode des trapèzes, étudiée ici, remplace tout arc de courbe correspondant à [xi,xi+1] par le segment [MiMi+1], donc l'aire sous la courbe, par « trapèze » xi Mi Mi+1 xi+1 au lieu du « rectangle » xi Mi Ni+1 xi+1 (figure de droite ci-dessus).

<p align="center"><img src=méthodetrapèzes.gif/></p>

     -simulation de ces trois méthodes :
 <p align="center"><img src=comparison3méthodes.gif/></p>

## Méthode de Simpson :

>La méthode de Simpson consiste à grouper trois points consécutifs de la courbe Mi, Mi+1 et Mi+2 et de remplacer l'arc de courbe passant par ces trois points par un arc de parabole. Notons que si les points Mi, Mi+1 et Mi+2 sont alignés, le calcul des paramètres de la parabole d'équation y = mx2 + px + q, passant par ces points conduira à m = 0. Par suite, quitte à parler de parabole dégénérée, ce cas n'est pas singulier.

<p align="center"><img src="image10.png"/></p>
  
    -simulation de ces quatre méthodes :

<p align="center"><img src=quatremethodes.gif/></p>

## Conclusion 
Plus que le nombre de subdivisions augmente, les valeurs sont plus proches des valeurs exactes.





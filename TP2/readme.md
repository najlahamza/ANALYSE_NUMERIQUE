
#  Interpolation Numérique


### Principe de l'interpolation polynomiale:

En mathématiques, en analyse numérique, l'interpolation polynomiale est une technique d'interpolation d'un ensemble de données ou d'une fonction par un polynôme. En d'autres termes, étant donné un ensemble de points (obtenu, par exemple, à la suite d'une expérience), on cherche un polynôme qui passe par tous ces points, et éventuellement vérifie d'autres conditions, de degré si possible le plus bas.

*  Principe de l'interpolation de Lagrange:

Le polynôme d’interpolation de Lagrange P(x) est le polynôme unique d’ordre n, qui passe exactement par ces (n+1) points,il permettent d'interpoler une série de points par un polynome:
> Soient <img src="https://render.githubusercontent.com/render/math?math=(x_0,y_0), \ldots,(x_k,y_k),\ldots ,(x_n,k_n)">  , le polynôme d'interpolation de Lagrange associés à ces points supports est défini par :
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle P_n(x)=\sum_{k=0}^{n%2B1} y_kL_k(x)">

avec


<img src="https://render.githubusercontent.com/render/math?math=L_{0}(x)=\displaystyle\frac{(x-x_1)(x-x_2)\ldots(x-x_{n})}{(x_0-x_1)(x_0-x_2)\ldots(x_0-x_{n})}">

et 


<img src="https://render.githubusercontent.com/render/math?math=L_{k}(x)=\displaystyle\frac{(x-x_1)(x-x_2)\ldots(x-x_{k-1})(x-x_{k%2B1})\ldots(x-x_{n})}{(x_k-x_0)(x_k-x_1)\ldots(x_k-x_{k-1})(x_k-x_{k %2B 1})\ldots(x_k-x_{n})}">


 pour 
 
 <img src="https://render.githubusercontent.com/render/math?math=k\in \{1,\ldots,n\}">


*  Principe de phénomène de Runge:

Le phénomène de Runge est la conséquence de deux propriétés du problème. L'amplitude des dérivées de la fonction de Runge augmente très rapidement lorsque n augmente. L'équi-répartition des points d'interpolation mène à une constante de Lebesgue qui augmente très rapidement lorsque n augmente.
<br>
*  Principe de polynome de Newton:

l'interpolation newtonienne, est une méthode d'interpolation polynomiale permettant d'obtenir le polynôme de Lagrange comme combinaison linéaire de polynômes de la « base newtonienne ».
<br>
l'interpolation polynomiale dans une base de Newton est une combinaison linéaire de polynômes appartenant à cette base.
<br><br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/najlahamza/ANALYSE_NUMERIQUE/main?labpath=https%3A%2F%2Fgithub.com%2Fnajlahamza%2FANALYSE_NUMERIQUE%2Fblob%2Fmain%2FTP2%2FTP2_E.ipynb)

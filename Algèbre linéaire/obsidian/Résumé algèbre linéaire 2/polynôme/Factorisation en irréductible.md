#### Définition
Un polynôme $p(x) \in \mathbb K[X]$ est dit *irréductible* si
1. $\deg p \geqslant 1$
2. Si pour $f,g \in \mathbb K[X]$ on a que $fg = p$ alors $\deg f = \deg p$ ou $\deg g = \deg p$

Ainsi d'après la notion de [[divisibilité et racine]] on a le théorème suivant

### Théorème
Soit $f(x) \in \mathbb K[X]$ de degré $2$ ou $3$ alors $f$ est irréductible si et seulement si $f$ ne possède pas de racines dans $\mathbb K$.

##### Corolaire
On a donc si $f(x) \in \mathbb K[X]$ et $\deg f \geqslant 1$ n'est pas irréductible alors il existe $f = p_1 p_2$ avec $\deg p_1, \deg P_1 \geqslant 1$ et $\deg p_1 + \deg p_2 = \deg f$. On peut donc continuer à factoriser les polynômes $p_1$ pour obtenir
$$ f = a \prod_{i=1}^l p_i$$
où $p_i \in \mathbb K[X]$ sont irréductible et unitaire et $a\in \mathbb K$. Cette factorisation est unique.

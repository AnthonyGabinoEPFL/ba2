#### Définition
Soit $v \in \mathbb K^n$ et $f(x) \in \mathbb K[X]$ un polynôme. On dit que $f$ *$A$-annule* $v$ si
$$ f(A) \cdot v = 0$$

Au même titre qu'on a l'existence et l'unicité d'un polynôme minimal pour la matrice $A$, on qu'il existe l'existence d'un polynôme $p(x) \in \mathbb K[X]$ non nul unitaire $A-annulateur$ de $v$ de degré maximal tel que $p(x)$ divise chaque $f(x)$ qui $A$-annule $v$. Et on le note $p_v(x)$ 

De plus on remarque que $p_v \mid \mu_A$ et que
$$ P(p_v(x) \neq \mu_A(x)) \leqslant \frac12$$
donc si on calcule $p_v(x)$ pour $v \in S^n$ $n$ fois, on obtient alors $n$ polynôme annulateur unitaire, on choisit celui de degré maximal $p(x)$ et la probabilité que ce polynôme choisit ne soit pas égal à $\mu_A$ est borné par
$$P(p(x) \neq \mu_A(x)) \leqslant \frac1{2^n}$$

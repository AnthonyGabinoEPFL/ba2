#### Définition
Soit $A \in  \mathbb K^{n \times n}$ et $p(x) \in \mathbb K[X]$, alors $p$ induit naturellement l'*évaluation* de $p$ est $A$ comme étant la matrice
$$ p(A) = a_0 I_n + a_1 A + a_2 A^2 + \ldots + a_n A^n$$
Il est facile de voir que $\phi : \mathbb K[X] \to \mathbb K^{n \times n}, p(x) \mapsto p(A)$ est un morphisme d'anneaux. Or on sait qu'un le noyau d'un morphisme anneau est un idéal bilatère principale car $K[X]$ est un anneaux principale. Donc il existe un unique polynôme unitaire $\mu_A \in \mathbb K[X]$ telle que
$$ \ker \phi = (\mu_A)$$
On appelle ce polynôme le *polynôme minimale* de $A$. Donc par définition
$$ \forall h \in \ker \phi, \quad \mu_A \mid h$$
et en particulier $\mu_A \mid \chi_A$ où $\chi_A$ désigne le [[polynôme caractéristique]] de $A$.

##### Question : [[Comment calculer le polynôme minimal]]?


### Théorème
Une matrice $A \in \mathbb K^{n \times n}$ est diagonalisable si et seulement son polynôme minimal est scindé simple.



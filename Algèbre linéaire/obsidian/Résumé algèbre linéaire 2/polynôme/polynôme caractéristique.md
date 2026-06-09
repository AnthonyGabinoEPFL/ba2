#### Définition
Soit $A \in \mathbb K^{n \times n}$, on définit le *polynôme caractéristique* de $A$ comme
$$ \chi_A (X) = \det (A - xI_n) \in \mathbb K[X]$$
On alors le théorème suivant
### Théorème de Cayley Hamilton
Soit $A \in \mathbb K^{n  \times n}$ alors
$$ \chi_A (A) = 0$$


## Étude des valeurs propres de $A$
Il est facile de voir que
$$ \lambda \text{ est valeur prore de } A \iff \chi_A(\lambda) = 0$$
Donc on définit la *multiplicité algébrique* de $\lambda$ comme étant la multiplicité de $\lambda$ comme racine de $\chi_A$ . D'ailleurs la multiplicité algébrique est au plus la multiplicité géométrique.

On peut donc en conclure qu'on a le théorème suivant
### Théorème de diagonalisation
Soit $A \in \mathbb K^{n \times n}$, alors $A$ est diagonalisable si et seulement si
1. Son polynôme caractéristique $\chi_A$ est scindé $$ \chi_A(x) = (-1)^n \prod_{i=1}^k (x - \lambda_k)^{\alpha_k}$$où $\alpha_i$ est la multiplicité algébrique de $\lambda_i \in \mathbb K$
2. Les multiplicités algébriques et géométrique sont les mêmes

>[!note]- Preuve
>uwu




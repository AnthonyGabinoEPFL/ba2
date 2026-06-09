Une matrice est dite *diagonalisable* s'il existe une matrice inversible $P \in \mathbb K^{n \times n}$ telle que
$$ A = P D P^{-1}$$
avec $D \in \mathbb K^{n \times n}$ une matrice diagonale.

On remarque facilement que $A$ est diagonalisable si et seulement si
$$ \sum_{i=1}^k \dim E_{\lambda_k} = n$$
car les sous-espace propre sont déjà en somme direct et donc avec cette condition on a
$$ V = \bigoplus_{i=1}^n E_{\lambda_k}$$
et donc $A$ dans cette nouvelle base, formé de vecteurs propres, est de la forme
$$ A' = \begin{pmatrix} \lambda_1 && \\ & \ddots &  \\ && \lambda_k \end{pmatrix}$$
et donc en posant $P = (v_1, \ldots, v_n)$ la matrice dont les colonnes sont données par les vecteurs propres de $A$ alors on a par construction
$$ A' = P^{-1} A P$$
d'où $A = P A' P^{-1}$. 

On a certes une condition nécessaire et suffisante mais pour autant cela reste fastidieux à trouver les valeurs propres et calculer la dimension des sous-espaces propres est relativement long. On a donc mieux, notamment en considérant le [[polynôme caractéristique]] et le [[polynôme minimal]]


### Théorème

#### Définition
Soit $V$ un $\mathbb K$ espace vectoriel, une *forme bilinéaire* et une application
$$ \begin{array}{cccc} \langle \cdot, \cdot \rangle : & V \times V & \to & V \\ & (u,v) & \mapsto & \langle u,v \rangle \end{array}$$
tel que $\langle \cdot, \cdot \rangle$ est linéaire en chacune des composantes. Soit $\mathcal B = \{b_1, \ldots, b_n\}$ une base de $V$, alors la matrice associé à $\langle \cdot, \cdot \rangle$ dans la base  $\mathcal B$ est donnée par
$$ (A_{\mathcal B}) = \langle b_i, b_j \rangle$$
et donc il est facile de voir que pour $u,v \in V$ alors
$$ \langle u,v \rangle = [u]_{\mathcal B}^\top A_{{\mathcal B}} [v]_{\mathcal B}$$
On sait que si on considère une autre base $\mathcal B'$ alors on a la matrice de changement de base $P_{B B'}$ 
$$ [u]_{\mathcal B} = P_{\mathcal B' \mathcal B} [u]_{\mathcal B'}$$
et donc
$$ \langle u, v \rangle = [u]_{\mathcal B'}^\top  P_{\mathcal B'B}^\top A_{\mathcal B} P_{B' B} [v]_{\mathcal B}$$
donc en conclut que
$$ A_{\mathcal B'} = P_{\mathcal B' B}^\top A_{\mathcal B} P_{\mathcal B'B}$$
Ainsi on peux définir la notion de [[matrices congruente]].

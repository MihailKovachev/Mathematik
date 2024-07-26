> [!TODO] Algorithmus: Basiswechsel in $K^n$
> Wir betrachten den [Vektor](Spaltenvektor.md) $\vec{v}\in K^n$. 
> 
> Wir haben seinen [Koordinatenvektor](../Abstrakte%20lineare%20Algebra/Basis/Koordinatenvektor.md) ${}_B \vec{v}$ bezüglich der geordneten Basis $B = (\vec{b}_1,\cdots,\vec{b}_n)$ und möchten seine Darstellung ${}_{B'}\vec{v}$ bezüglich einer anderen Basis $B' = (\vec{b}_1',\cdots,\vec{b}_n')$ finden.
> 
> Wir folgen dabei dem [allgemeinen Basiswechselalgorithmus](../Abstrakte%20lineare%20Algebra/Basis/Basiswechsel.md).
> 
> 1. Anhand [dieses Verfahren](Bestimmen%20einer%20Basisdarstellung.md) bestimmen wir die Koordinatenvektoren ${}_{B'}\vec{b}_1,\cdots,{}_{B'}\vec{b}_n$ von $\vec{b}_1,\cdots,\vec{b}_n$ bezüglich der Basis $B'$.
> 2. Wir notieren die Matrizendarstellung des Basiswechsels
> $${}_{B'}[I_n]_{B} = \begin{bmatrix}\vert & \vert & \vert \\ {}_{B'}\vec{b}_1 & \cdots & {}_{B'}\vec{b}_n \\ \vert & \vert & \vert\end{bmatrix}$$
> 3. Wir multiplizieren ${}_B \vec{v}$ mit ${}_{B'}[I_n]_{B}$.
> $${}_{B'}\vec{v} = {}_{B'}[I_n]_{B}\cdot {}_B\vec{v}$$
> 
> > [!EXAMPLE]- Beispiel
> > 


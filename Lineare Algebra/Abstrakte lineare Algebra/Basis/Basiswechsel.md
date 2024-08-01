> [!ALGORITHM] Algorithmus: Basiswechsel
> Wir haben den [Koordinatenvektor](Koordinatenvektor.md) ${}_{B}\mathbf{v}$ eines [Vektors](../Abstrakter%20Vektorraum.md) $\mathbf{v}$ bezüglich der [Basis](Basis.md) $B = (\mathbf{b}_1,\cdots,\mathbf{b}_n)$ und möchten den Koordinatenvektor ${}_{B'}\mathbf{v}$ von $\mathbf{v}$ bezüglich der Basis $B' = (\mathbf{b}_1',\cdots,\mathbf{b}_n')$ bestimmen.
> 
> > [!THEOREM] Satz
> > An den Basiswechsel kann man als die [lineare Transformation](../Lineare%20Transformationen/Lineare%20Transformation.md) $T: V \to V$ denken, die einfach nichts tut:
> > $$T(\mathbf{v}) = \mathbf{v}$$
> > Die [Matrizendarstellung](../Lineare%20Transformationen/Matrizendarstellung.md) ${}_{B'}[I_n]_B$ können wir aber so bestimmen, das sie Koordinatenvektoren bezüglich $B$ in Koordinatenvektoren bezüglich $B'$ verwandelt.
> > > [!NOTE] Schreibweise
> > > Das Symbol $I_n$ für die [Einheitsmatrix](../../Matrizen/Quadratische%20Matrizen/Einheitsmatrix.md) benutzt man, um klarer werden zu lassen, dass der Basiswechsel den Vektor $\mathbf{v}$ nicht ändert und dass er nur die Koordinatenvektoren betrifft.
> 
> Dazu folgen wir dem [Algorithmus zum Bestimmen der Matrizendarstellung einer linearen Transformation](../Lineare%20Transformationen/Matrizendarstellung.md).
> 
> 1. Dazu müssen wir wissen, was für eine Auswirkung $T$ auf die Basisvektoren $\mathbf{b}_1,\cdots,\mathbf{b}_n$ hat. Das ist einfach 
> $$T(\mathbf{b}_1) = \mathbf{b}_1 \qquad \cdots \qquad T(\mathbf{b}_n) = \mathbf{b}_n$$
> 2. Außerdem müssen wir die Koordinatenvektoren von $T(\mathbf{b}_1), \cdots, T(\mathbf{b}_n)$ bezüglich der Ausgangsbasis $B'$ wissen, d.h. wir brauchen die Koordinatenvektoren ${}_{B'}\mathbf{b}_1,\cdots,{}_{B'}\mathbf{b}_n$.
> - Dieser Schritt hängt vom Vektorraum $V$ ab.
> - Falls $V$ [euklidisch](../Euklidische%20Vektorräume/Abstraktes%20inneres%20Produkt.md) ist und $B_W$ eine [Orthonormalbasis](Orthonormalbasis.md) ist, kann man zum Bestimmen von ${}_{B'}\mathbf{b}_1,\cdots,{}_{B'}\mathbf{b}_n$ [diesen Satz](Basisdarstellung%20durch%20Orthonormalbasis.md) ausnutzen.
> 3. Wir notieren die Matrizendarstellung
> $${}_{B'}[I_n]_{B} = \begin{bmatrix}\vert & \vert & \vert \\ {}_{B'}T(\mathbf{b}_1) & \cdots & {}_{B'}T(\mathbf{b}_n) \\ \vert & \vert & \vert\end{bmatrix} = \begin{bmatrix}\vert & \vert & \vert \\ {}_{B'}\mathbf{b}_1 & \cdots & {}_{B'}\mathbf{b}_n \\ \vert & \vert & \vert\end{bmatrix}$$
> 4. Wir können jetzt jeden Koordinatenvektor ${}_{B}\mathbf{v}$ bezüglich der Basis $B$ in seinen entsprechenden Koordinatenvektor ${}_{B'}\mathbf{v}$ bezüglich der Basis $B'$ verwandeln, indem wir ihn mit ${}_{B'}[I_n]_{B}$ multiplizieren.
> $${}_{B'}\mathbf{v} = {}_{B'}[I_n]_{B}\cdot {}_{B}\mathbf{v}$$
> 
> > [!EXAMPLE]- Beispiel: [Basiswechsel in $K^n$](../../Vektoren%20als%20Matrizen/Basiswechsel.md)
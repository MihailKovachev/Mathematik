> [!IMPORTANT] Satz: Darstellung als Matrizen
> Jede [lineare Transformation](Lineare%20Transformation.md) $T: V \to W$ vom [Vektorraum](../Abstrakter%20Vektorraum.md) $(V,K,+,\cdot)$ in den Vektorraum $(W,K,+,\cdot)$ lässt sich als eine [Matrix](../../Matrizen/Matrix.md) $M_T\in K^{\dim(W)\times \dim(V)}$ darstellen.
> 
> Seien $B_V$ und $B_W$ *geordnete [Basen](../Basis/Basis.md)* von jeweils $V$ und $W$. Für jeden Vektor $\mathbf{v}\in V$ gilt
> $$T(\mathbf{v}) = M_T\cdot {}_{B_V}\mathbf{v},$$
> wo ${}_{B_V}\mathbf{v}$ der [Koordinatenvektor](../Basis/Koordinatenvektor.md) von $\mathbf{v}$ bezüglich der Basis $B_V$ ist.
> 
> > [!WARNING] Warnung: Abhängigkeit von Basen
> > Die Matrix $M_T$ hängt von den [Basen](../../Abstrakte%20lineare%20Algebra/Basis/Basis.md) für die [Vektorräume](../../Abstrakte%20lineare%20Algebra/Abstrakter%20Vektorraum.md) $V$ und $W$ ab, durch die die Vektoren dargestellt werden.
> > 
> > Um dies klarer werden zu lassen, notieren wir oftmals 
> > $${}_{B_{W}}[M_T]_{B_{V}}$$ 

> [!TODO] Algorithmus: Konstruieren der Matrizendarstellung
> Sei $T: V\to W$ eine [lineare Transformation](Lineare%20Transformation.md). Wir wählen auch eine [Basis](../Basis/Basis.md) $B_V = (\mathbf{b}_1^V,\cdots,\mathbf{b}_m^V)$ von $V$ und eine Basis $B_W = (\mathbf{b}_1^W,\cdots,\mathbf{b}_n^W)$ von $W$. 
> 
> Wir suchen nach derjenigen Matrix ${}_{B_W}[M_T]_{B_V}$, die durch $B_V$ dargestellte Vektoren anhand von $T$ transformiert und das Ergebnis durch $B_W$ äußert.
> 1. Bestimme die Auswirkung von $T$ auf die Basisvektoren $(\mathbf{b}_1^V,\cdots,\mathbf{b}_m^V)$. Man braucht also zu wissen
> $$\mathbf{w}_1 = T(\mathbf{b}_1^V) \qquad \cdots \qquad \mathbf{w}_m = T(\mathbf{b}_m^V)$$
> 2. Bestimme die [Koordinatenvektoren](../Basis/Koordinatenvektor.md) ${}_{B_W}\mathbf{w}_1,\cdots,{}_{B_W}\mathbf{w}_m$ von $\mathbf{w}_1,\cdots,\mathbf{w}_n$ bezüglich der von uns gewählten Basis $B_W$.
> - Wie man das erzielt, hängt von den Vektorräumen ab, und es gibt kein allgemeines Verfahren dafür.
> - Falls $B_W$ eine [Orthonormalbasis](../Basis/Orthonormalbasis.md) ist, kann man dazu [diesen Satz](../Basis/Basisdarstellung%20durch%20Orthonormalbasis.md) ausnutzen.
> 3. Notiere die Matrix $M_T$, indem du die Koordinatenvektoren ${}_{B_W}\mathbf{w}_1,\cdots, {}_{B_W}\mathbf{w}_m$ für die Spalten der Matrix einsetzt. 
> $$M_T = \begin{bmatrix}\vert & \vert & \vert \\ {}_{B_W}\mathbf{w}_1 & \cdots & {}_{B_W}\mathbf{w}_m \\ \vert & \vert & \vert \end{bmatrix} = \begin{bmatrix}\vert & \vert & \vert \\ {}_{B_W}T(\mathbf{b}_1^V) & \cdots & {}_{B_W}T(\mathbf{b}_m^V) \\ \vert & \vert & \vert \end{bmatrix}$$
> 
> > [!EXAMPLE]- Beispiel
> > Wir betrachten die lineare Transformation $T: \mathbb{R}^3\to\mathbb{R}^3$, die die [Länge](../Euklidische%20Vektorräume/Norm%20(Länge).md) ihres Eingangsvektors verdoppelt und ihn umdreht.
> > 
> > 1. Wir wählen die [Standardbasis](../../Geometrische%20Aspekte/Standardbasis.md) sowohl als Eingangs- als auch als Ausgangsbasis. 
> > - Wir beschreiben die Auswirkung von $T$ auf die Basisvektoren $\hat\imath, \hat\jmath, \hat k$.
> > $$T(\hat\imath) = T\left(\begin{bmatrix}1 \\ 0 \\ 0\end{bmatrix}\right) = \begin{bmatrix}-2 \\ 0 \\ 0\end{bmatrix}$$
> > $$T(\hat\jmath) = T\left(\begin{bmatrix}0 \\ 1 \\ 0\end{bmatrix}\right) = \begin{bmatrix}0 \\ -2 \\ 0\end{bmatrix}$$
> > $$T(\hat k) = T\left(\begin{bmatrix}0 \\ 0 \\ 1\end{bmatrix}\right) = \begin{bmatrix}0 \\ 0 \\ -2\end{bmatrix}$$
> > - Diese Ausgangsvektoren sind schon durch die Standardbasis dargestellt, weshalb wir nicht brauchen, andere Koordinatenvektoren zu bestimmen.
> > - Wir notieren nun
> > $$M_T = \begin{bmatrix}\vert & \vert & \vert \\ T(\hat\imath) & T(\hat \jmath) & T (\hat k) \\ \vert & \vert & \vert\end{bmatrix} = \begin{bmatrix}-2 & 0 & 0 \\ 0 & -2 & 0 \\ 0 & 0 & -2\end{bmatrix}$$
> > 
> > 2. Wir wählen die Standardbasis als Eingangsbasis aber $\left(\begin{bmatrix}1 \\ 0 \\ 0\end{bmatrix}, \begin{bmatrix}1 \\ 1\\ 0\end{bmatrix}, \begin{bmatrix}1 \\ 1 \\ 1\end{bmatrix}\right)$ als Ausgangsbasis.
> [!DANGER] Definition: Spaltenvektor
> Die $m\times 1$-[Matrix](../Matrizen/Matrix.md)
> $$\vec{v} = \begin{bmatrix}v_1 \\ \vdots \\ v_m\end{bmatrix} \in K^{m\times 1} = K^m$$
> nennt man **Spaltenvektor**.

> [!IMPORTANT] Satz: Spaltenvektoren als Koordinatenvektor
> Der Spaltenvektor $\vec{v} = \begin{bmatrix}v_1 & \cdots & v_m\end{bmatrix}^\mathsf{T}\in K^m$ ist auch der [Koordinatenvektor](../Abstrakte%20lineare%20Algebra/Basis/Koordinatenvektor.md) von $\vec{v}$ bezüglich der [Standardbasis](../Geometrische%20Aspekte/Standardbasis.md) von $K^m$.
> > [!CHECK]- Beweis
> > Für jeden $\vec{v} = \begin{bmatrix}v_1 & \cdots & v_m\end{bmatrix}^\mathsf{T}$ gilt
> > $$v_1\begin{bmatrix}1 \\ 0 \\ \vdots \\ 0 \\ 0\end{bmatrix} + \cdots + v_i\begin{bmatrix}0 \\ \vdots \\ 1 \\ \vdots \\ 0\end{bmatrix}+ \cdots + v_m\begin{bmatrix} 0 \\ 0 \\ \vdots \\ 0 \\ 1\end{bmatrix} = \begin{bmatrix}v_1 \\ \vdots \\ v_i \\ \vdots \\ v_m\end{bmatrix}$$
> 
> > [!NOTE] Notiz
> > Wegen dieser Äquivalenz werden die Begriffe "Spaltenvektor" und "Koordinatenvektor" synonym, wenn es sich um die Standardbasis handelt.
> > 
> > Wenn es stattdessen um eine andere Basis $B$ geht, wird dies durch den Koordinatenvektor ${}_B \vec{v}$ von $\vec{v}$ bezüglich $B$ bezeichnet. In diesem Fall unterscheiden sich die Komponenten des Spaltenvektors $\vec{v}$ und des Koordinatenvektors ${}_{B}\vec{v}$.
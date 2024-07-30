> [!DANGER] Definition: Diagonalisierbarkeit
> Eine [quadratische Matrix](../../Quadratische%20Matrix.md) $M\in K^{n\times n}$ heißt **diagonalisierbar**, falls es eine [invertierbare](../../../Invertieren/Invertierbarkeit.md) Matrix $Q\in K^{n\times n}$ gibt, sodass
> $$\Lambda \overset{\text{def}}{=} Q^{-1}MQ$$
> eine [Diagonalmatrix](../../Diagonalmatrix.md) ist.
> 
> Man nennt:
> - $\Lambda \in K^{n\times n}$ eine **Diagonalform** zu $M$;
> - $Q$ eine $A$ **diagonalisierende Matrix**;
> - das Bestimmen von $\Lambda$ und $Q$ das **Diagonalisieren von** $M$.

> [!IMPORTANT] Satz: Diagonalisierbarkeitskriterium I
> Eine [quadratische Matrix](../../Quadratische%20Matrix.md) $M\in K^{n\times n}$ ist genau dann [diagonalisierbar](Diagonalisierbarkeit.md), wenn es eine [Eigenbasis](Eigenbasis.md) $B_\lambda = (\vec{e}_{\lambda_1},\cdots,\vec{e}_{\lambda_n})$ von $K^n$ von $M$ gibt.
> 
> - Die [Diagonalform](Diagonalisierbarkeit.md) $\Lambda$ von $M$ hat die [Eigenwerte](Eigenwert.md) $\lambda_1,\cdots,\lambda_n$ von $M$ auf der Diagonale.
> $$\Lambda = \operatorname{diag}(\lambda_1,\cdots,\lambda_n)$$
> 
> - Die $M$ [diagonalisierende Matrix](Diagonalisierbarkeit.md) $Q$ hat die [Eigenvektoren](Eigenvektor.md) $(\vec{e}_{\lambda_1}, \cdots, \vec{e}_{\lambda_n})$ aus der [Eigenbasis](Eigenbasis.md) $B_\lambda$ als Spalten.
> $$Q = \begin{bmatrix}\vert & \vert & \vert \\ \vec{e}_{\lambda_1} & \cdots & \vec{e}_{\lambda_n}\\ \vert & \vert & \vert\end{bmatrix}$$
> 
> > [!CHECK]- Beweis

> [!IMPORTANT] Satz: Diagonalisierbarkeitskriterium II
> Eine [quadratische Matrix](../../Quadratische%20Matrix.md) $M$ ist genau dann diagonalisierbar, wenn die [geometrische](Eigenwert.md) und [algebraische](Eigenschaften%20des%20charakteristischen%20Polynoms.md) Vielfachheit für jeden [Eigenwert](Eigenwert.md) von $M$ gleich sind.
> > [!CHECK]- Beweis
> 
> > [!IMPORTANT] Folgerung
> > Jede [quadratische Matrix](../../Quadratische%20Matrix.md) $M\in K^{n\times n}$ mit $n$ verschiedenen [Eigenwerten](Eigenwert.md) ist diagonalisierbar.
> > 
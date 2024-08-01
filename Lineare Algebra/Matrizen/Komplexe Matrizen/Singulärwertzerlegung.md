> [!THEOREM] Satz: Singulärwertzerlegung
> Jede [komplexe Matrix](Komplexe%20Matrix.md) $M\in\mathbb{C}^{n\times m}$ lässt sich als [Multiplikation](../Matrizenoperationen/Multiplikation%20von%20Matrizen.md)
> $$M = U\Sigma V^\dagger$$
> dreier [Matrizen](../Matrix.md) darstellen, wobei $U\in\mathbb{C}^{m\times m}$ und $V\in\mathbb{C}^{n\times n}$ zwei [unitäre Matrizen](Unitäre%20Matrizen/Unitäre%20Matrix.md) sind.
> 
> Die [Matrix](../Matrix.md) $\Sigma$ hat folgende Gestalt:
> - Im Falle $m\le n$
> $$\Sigma = \begin{bmatrix}\sigma_1 & \cdots & 0 & 0 & \cdots & 0 \\ \vdots & \ddots & \vdots & \vdots & \ddots & \vdots \\ 0 & \cdots & \sigma_m & 0 & \cdots & 0 \end{bmatrix}$$
> 
> - Im Falle $n \le m$
> $$\Sigma = \begin{bmatrix}\sigma_1 & \cdots & 0 \\ \vdots & \ddots & \vdots \\  0 & \cdots & \sigma_n \\ 0 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 0\end{bmatrix}$$
> > [!PROOF]- Beweis
> 
> > [!DEFINITION] Definition: Singulärwertzerlegung
> > Die Darstellung $M = U\Sigma V^\dagger$ nennt man **Singulärwertzerlegung** von $M$.
> 
> > [!DEFINITION] Definition: Singulärwert
> > Die Einträge $\sigma_i \ge 0$ nennt man **Singularwerte** von $M$.
> 
> > [!DEFINITION] Definition: Singulärvektor
> > Die [Spalten](../../Vektoren%20als%20Matrizen/Spaltenvektor.md) von $U$ heißen **Links-Singulärvektoren** und die [Spalten](../../Vektoren%20als%20Matrizen/Spaltenvektor.md) von $V$ heißen **Rechts-Singulärvektoren** von $M$.
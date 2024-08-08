>[!THEOREM] Satz: Richtungsableitung in beliebige Richtung
>Sei $f: D\subseteq\mathbb{R}^n\to\mathbb{R}$ ein [Skalarfeld](Skalarfeld.md) und $\vec{x}\in D$.
>
>Sind alle [partiellen Ableitungen](Differentiation/Partielle%20Ableitung.md) von $f$ stetig in $\vec{x}$, so ist die [Richtungsableitung](Richtungsableitung.md) $\partial_{\vec{r}} f(\vec{x})$ in jede beliebige Richtung $\vec{r}$ mit $||\vec{r}|| = 1$ gleich dem [Skalarprodukt](../../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Kanonisches%20Skalarprodukt.md) von $\vec{r}$ und dem [Gradienten](Gradient.md) von $f$ in $\vec{x}$.
>$$\frac{\partial f}{\partial{\vec{r}}} (\vec{x}) = \left\langle \nabla f(\vec{x}),\vec{r}\right\rangle$$
>>[!PROOF]- Beweis

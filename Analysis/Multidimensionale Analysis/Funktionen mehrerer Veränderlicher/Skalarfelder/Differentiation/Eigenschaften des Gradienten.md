>[!THEOREM] Satz: Richtung des stärksten Anstiegs und des stärksten Abnehmens
>Sei $f: D\subseteq \mathbb{R}^n \to \mathbb{R}$ ein [partiell differenzierbares](Partielle%20Differenzierbarkeit.md) [Skalarfeld](../Skalarfeld.md).
>
>In jedem $\vec{x} \in D$:
>- ist die größte [Richtungsableitung](Richtungsableitung.md) von $f$ in Richtung des [Gradienten](Gradient.md) $\nabla f(\vec{x})$ orientiert;
>- ist die kleinste [Richtungsableitung](Richtungsableitung.md) von $f$ in Richtung des negativen [Gradienten](Gradient.md) $-\nabla f(\vec{x})$ orientiert.
>
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Richtungsableitung in beliebige Richtung
>Seien $f: D\subseteq\mathbb{R}^n\to\mathbb{R}$ [Skalarfeld](Skalarfeld.md) und $\vec{x}\in D$.
>
>Falls alle [partiellen Ableitungen](Differentiation/Partielle%20Ableitung.md) von $f$ stetig in $\vec{x}\in D$ sind, so ist die [Richtungsableitung](Richtungsableitung.md) $\partial_{\hat{r}} f(\vec{x})$ in jede beliebige Richtung $\hat{r}$ gleich dem [Skalarprodukt](../../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Kanonisches%20Skalarprodukt.md) von $\hat{r}$ und dem [Gradienten](Partielle%20Differenzierbarkeit.md) von $f$ in $\vec{x}$.
>$$\partial_{\hat{r}} f (\vec{x}) = \left\langle \nabla f(\vec{x}),\hat{r}\right\rangle$$
>>[!PROOF]- Beweis

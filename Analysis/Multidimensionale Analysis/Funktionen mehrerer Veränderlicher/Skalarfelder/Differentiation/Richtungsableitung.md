>[!DEFINITION] Definition: Richtungsableitung
>Sei $f: D\subseteq \mathbb{R}^n\to\mathbb{R}$ ein [Skalarfeld](Skalarfeld.md) und seien $\vec{x}\in D$ und $\vec{r}$ mit $||\vec{r}|| = 1$.
>
>Die **Richtungableitung** von $f$ in $\vec{x}$ in Richtung $\vec{r}$ ist
>$$\lim_{h\to 0}\frac{f(\vec{x}+h\cdot \vec{r})-f(\vec{x})}{h},$$
>falls dieser [Grenzwert](../../../../Eindimensionale%20Analysis/Grenzwerte%20von%20Funktionen/Grenzwerte.md) existiert.
>
>>[!NOTE] Bezeichnung
>>$$\frac{\partial f}{\partial \vec{r}}(\vec{x}) \qquad \partial_{\vec{r}}f \qquad (\vec{x}) \qquad f_{\vec{r}}(\vec{x})$$
>
>Die [Funktion](Skalarfeld.md) $\frac{\partial f}{\partial \vec{r}}$, die jedem $\vec{x}\in D$ seine Richtungsableitung in Richtung $\vec{r}$ zuordnet, nennt man auch Richtungsableitung.
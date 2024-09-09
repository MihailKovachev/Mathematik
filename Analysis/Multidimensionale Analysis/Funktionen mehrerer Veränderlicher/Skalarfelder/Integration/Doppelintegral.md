>[!DEFINITION] Definition: Doppelintegral über einem Rechteck
>Seien $R: [a;b]\times [c;d]\subseteq\mathbb{R}^2$ ein Rechteck und $f:R\to\mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md).
>
>Das **Doppelintegral** von $f$ über $R$ ist der [Grenzwert](../../../../Eindimensionale%20Analysis/Grenzwerte%20von%20Funktionen/Konvergenz%20von%20Funktionen.md) aller [Doppel-Riemann-Summen](Doppel-Riemann-Summe.md) von $f$, falls dieser existiert.
>
>$$\iint\limits_R f(x,y)\mathop{\mathrm{d}A} \overset{\text{def}}{=} \lim_{m,n\to\infty} \sum_{i=1}^m\sum_{j=1}^n f(x_{ij}^\ast, y_{ij}^\ast) \Delta A$$
>

>[!DEFINITION] Definition: Doppelintegral über einem willkürlichen Bereich
>Seien $D\subseteq \mathbb{R}^2$ ein Bereich in $\mathbb{R}^2$ und $R$ ein Rechteck in $\mathbb{R}^2$, das $D$ völlig umfasst.
>
>Das **Doppelintegral** des [Skalarfeldes](../Skalarfeld.md) $f: D\to\mathbb{R}$ über dem Bereich $D$ ist
>
>$$\iint\limits_D f(x,y)\mathop{\mathrm{d}A} \overset{\text{def}}{=} \iint\limits_R \mathcal{F}(x,y)\mathop{\mathrm{d}A}$$
>
>mit
>$$\mathcal{F}(x,y) = \begin{cases}f(x,y), \qquad \text {falls } (x,y)\in D \\ 0, \qquad\qquad \text{ falls } (x,y) \in R\setminus D\end{cases}$$


>[!NOTE] Notiz: Geometrische Bedeutung des Doppelintegrals
>Das Doppelintegral von $f$ über $D$ ergibt den *signierten* Volumeninhalt zwischen $D$ und der von $f$ beschriebenen Fläche.
>
>![](Resources/Geometrische%20Bedeutung%20des%20Doppelintegrals%20über%20einem%20Bereich.png)
>[!THEOREM] Fubini's Satz
>Seien $R = [a;b]\times[c;d]\subseteq\mathbb{R}^2$ ein Rechteck und $f: R\to\mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md),
>
>Falls $f$ [stetigkeit](../Stetigkeit%20von%20Skalarfeldern.md) auf $R$ ist, so lässt sich das [Doppelintegral](Doppelintegral.md) von $f$ über $R$ anhand iterierter Integrale berechnen:
>
>$$\iint\limits_R f(x,y) \mathop{\mathrm{d}A} = \int_c^d \int_{a}^b f(x,y)\mathop{\mathrm{d}x}\mathop{\mathrm{d}y} = \int_{a}^b \int_c^d f(x,y)\mathop{\mathrm{d}y}\mathop{\mathrm{d}x}$$
>
>>[!PROOF]- Beweis
>>TODO

>[!THEOREM] Satz: Doppelintegrale über Normalbereiche
>Sei $f: D\subseteq\mathbb{R}^2 \to\mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md).
>
>Ist $D$ ein [Normalbereich](../../../../../Topologie/Normalbereich.md) der Form $D = \{(x,y)\mid a\le x \le b, u(x) \le y \le o(x)\}$, so lässt sich das [Doppelintegral](Doppelintegral.md) von $f$ über $D$ durch ein iteriertes Integral berechnen:
>
>$$\iint\limits_D f(x,y) \mathop{\mathrm{d}A} = \int_a^b \int_{u(x)}^{o(x)} f(x, y) \mathop{\mathrm{d}y}\mathop{\mathrm{d}x}$$
>
>Ist $D$ ein [Normalbereich](../../../../../Topologie/Normalbereich.md) der Form $D = \{(x,y)\mid u(y)\le x \le o(y), a \le y \le b\}$, so lässt sich das [Doppelintegral](Doppelintegral.md) von $f$ über $D$ durch ein iteriertes Integral berechnen:
>
>$$\iint\limits_D f(x,y) \mathop{\mathrm{d}A} = \int_a^b \int_{u(y)}^{o(y)} f(x, y) \mathop{\mathrm{d}x}\mathop{\mathrm{d}y}$$
>
>>[!PROOF]- Beweis
>>TODO

>[!THEOREM] Satz: Bereichzerlegung
>Seien $D\subseteq\mathbb{R}^2$ ein Bereich von $\mathbb{R}^2$ und $f: D\to\mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md).
>
>Falls $D$ als disjunkte Vereinigung $D = D_1\cup\cdots\cup D_n$ endlich vieler [Normalbereiche](../../../../../Topologie/Normalbereich.md) darstellen lässt, so lässt sich das [Doppelintegral](Doppelintegral.md) von $f$ über $D$ in Doppelintegrale über die Normalbereiche zerlegen.
>
>$$\iint\limits_D f(x,y) \mathop{\mathrm{d}A} = \iint\limits_{D_1} f(x,y) \mathop{\mathrm{d}A} + \cdots + \iint\limits_{D_n} f(x,y) \mathop{\mathrm{d}A}$$
>
>>[!PROOF]- Beweis
>>TODO

>[!THEOREM] Satz: Linearität des Doppelintegrals
>Seien $D\subset\mathbb{R}^2$ ein [Normalbereich](../../../../../Topologie/Normalbereich.md) und $f,g: D\to\mathbb{R}$ zwei [Skalarfelder](../Skalarfeld.md).
>
>Für alle $\lambda,\mu\in\mathbb{R}$ ist das [Doppelintegral](Doppelintegral.md) linear:
>
>$$\iint\limits_D \lambda\,f(x,y) + \mu\, g(x,y)\mathop{\mathrm{d}A} = \lambda \iint \limits_D f(x,y) \mathop{\mathrm{d}A} \,\, + \,\, \mu \iint\limits_D g(x,y)\mathop{\mathrm{d}A}$$
>
>>[!PROOF]- Beweis
>>TODO

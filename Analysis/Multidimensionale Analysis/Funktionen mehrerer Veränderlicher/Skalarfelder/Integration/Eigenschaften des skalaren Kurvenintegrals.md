>[!THEOREM] Satz: Linearität des skalaren Kurvenintegrals
>Sei $\mathcal{C}$ eine [Kurve](../../Kurven/Kurve.md).
>
>Für alle $\lambda,\mu\in\mathbb{R}$ und alle [Skalarfelder](../Skalarfeld.md) $f,g:D\subseteq\mathbb{R}^n\to\mathbb{R}$ gilt für das [skalare Kurvenintegral](Skalares%20Kurvenintegral.md)
>$$\int_\mathcal{C} (\lambda\, f +\mu \, g)\mathop{\mathrm{d}s} = \lambda\int_\mathcal{C} f\mathop{\mathrm{d}s} + \mu \int_\mathcal{C} g\mathop{\mathrm{d}s} $$
>>[!PROOF]- Beweis
>>Laut Definition
>>$$\begin{align}\int_\gamma (\lambda\, f +\mu \, g)\mathop{\mathrm{d}s} &=\int_a^b [\lambda\, f(\gamma(t)) +\mu \, g(\gamma(t))]\,||\dot{\gamma}(t)||\mathop{\mathrm{d}t} \\ &=\int_a^b \lambda\, f(\gamma(t))\,||\dot{\gamma}(t)|| +\mu \, g(\gamma(t))\,||\dot{\gamma}(t)||\mathop{\mathrm{d}t} \\ &= \lambda \int_a^b f(\gamma(t)) \, ||\dot{\gamma}(t)|| \mathop{\mathrm{d}t} + \mu \int_a^b g(\gamma(t))\,||\dot{\gamma}(t)||\mathop{\mathrm{d}t} \\ &= \lambda\int_\gamma f\mathop{\mathrm{d}s} + \mu \int_\gamma g\mathop{\mathrm{d}s} \end{align}$$

>[!THEOREM] Satz: Zerlegungsadditivität des skalaren Kurvenintegrals
>Seien $f: D \subseteq \mathbb{R}^n \to \mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md) und $\mathcal{C} \subseteq D$ eine [Kurve](../../Kurven/Kurve.md). 
>
>Falls sich $\mathcal{C}$ als disjunkte [Vereinigung](../../../../../Mengenlehre/Operationen%20mit%20Mengen/Vereinigung.md) $\mathcal{C} = \mathcal{C}_1 \cup \cdots \cup \mathcal{C}_k$ anderer [Kurven](../../Kurven/Kurve.md) darstellen lässt, so lässt sich das [skalare Kurvenintegral](Skalares%20Kurvenintegral.md) von $f$ längs $\mathcal{C}$ in eine Summe der skalaren Kurvenintegrale von $f$ längs $\mathcal{C}_1,\cdots,\mathcal{C}_k$ zerlegen:
>
>$$\int_{\mathcal{C}} f\mathop{\mathrm{d}s} = \int_{\mathcal{C}_1} f\mathop{\mathrm{d}s} + \cdots + \int_{\mathcal{C}_k} f\mathop{\mathrm{d}s}$$
>
>>[!PROOF]- Beweis

>[!THEOREM] Mittelwertsatz für skalare Kurvenintegrale
>Seien $f: D \subseteq \mathbb{R}^n \to \mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md) und $\mathcal{C} \subseteq D$ eine [Kurve](../../Kurven/Kurve.md).
>
>Ist $f$ [stetig](../Stetigkeit%20von%20Skalarfeldern.md), so existiert mindestens ein Kurvenpunkt $\vec{x}\in \mathcal{C}$, sodass sich das [skalare Kurvenintegral](Skalares%20Kurvenintegral.md) von $f$ längs $\mathcal{C}$ als Produkt von $f(\vec{x})$ und der [Kurvenlänge](../../Kurven/Länge%20von%20Kurven.md) $L$ darstellen lässt:
>
>$$\int_\mathcal{C} f\mathop{\mathrm{d}s} = f(\vec{x})\cdot L$$
>
>>[!PROOF]- Beweis
>>Sei $\gamma: [a;b] \to \mathbb{R}^n$ eine [Parametrisierung](../../Kurven/Kurve.md) von $\mathcal{C}$. Das skalare Kurvenintegral von $f$ längs $\mathcal{C}$ ist dann
>>
>>$$\int_a^b f(\gamma(t))||\dot{\gamma}(t)||\mathop{\mathrm{d}t}$$
>>
>>Die Funktion $f$ ist nach Voraussetzung stetig. Ebenfalls ist $||\dot{\gamma}(t)||$ stetig und es gilt auch $||\dot{\gamma}(t)|| \ge 0$ für alle $t\in [a;b]$. Laut [diesem Mittelwertsatz](../../../../Eindimensionale%20Analysis/Integration/Bestimmte%20Integrale/Mittelwertsatz%20der%20Integralrechnung.md) gibt es deshalb ein $\xi \in [a;b]$ mit
>>
>>$$\int_a^b f(\gamma(t))||\dot{\gamma}(t)||\mathop{\mathrm{d}t} = f(\gamma(\xi)) \int_a^b ||\dot{\gamma}(t)||\mathop{\mathrm{d}t}$$
>>
>>Aus der rechten Seite ergeben sich der Kurvenpunkt $\vec{x}$ und die Kurvenlänge $L$:
>>$$\vec{x} \overset{\text{def}}{=} \gamma(\xi)$$
>>$$L = \int_a^b ||\dot{\gamma}(t)||\mathop{\mathrm{d}t}$$
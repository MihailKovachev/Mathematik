>[!THEOREM] Satz: Linearität des skalaren Kurvenintegrals
>Sei $\gamma: [a;b]\to\mathbb{R}^n$ eine [Kurve](../../Kurven/Kurve.md).
>
>Für alle $\lambda,\mu\in\mathbb{R}$ und alle [Vektorfelder](../Vektorfeld.md) $\boldsymbol{v},\boldsymbol{w}:D\subseteq\mathbb{R}^n\to\mathbb{R}^n$ gilt für das [vektorielle Kurvenintegral](Vektorielles%20Kurvenintegral.md)
>$$\int_\gamma (\lambda\, \boldsymbol{v} +\mu \, \boldsymbol{w})\cdot\mathop{\mathrm{d}s} = \lambda\int_\gamma \boldsymbol{v}\cdot\mathop{\mathrm{d}s} + \mu \int_\gamma \boldsymbol{w}\cdot \mathop{\mathrm{d}s} $$
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Zerlegungsadditivität des skalaren Kurvenintegrals
>Seien $\gamma_{|[a;c]}:[a;c]\to\mathbb{R}^n$ und $\gamma_{|[c;b]}:[c;b]\to\mathbb{R}^n$ zwei [Kurven](../../Kurven/Kurve.md) mit $\gamma_{|[a;c]}(c) = \gamma_{|[c;b]}(c)$ und sei $\gamma:[a;b]$ die aus $\gamma_{|[a;c]}$ und $\gamma_{|[c;b]}$ zusammengesetzte [[Kurve]].
> $$\gamma(t) = \begin{cases}\gamma_{|[a;c]}(t) \qquad t \in [a;c] \\ \gamma_{|[c;b]}(t) \qquad t\in [c;b]\end{cases}$$
>
>Für das [vektorielle Kurvenintegral](Vektorielles%20Kurvenintegral.md) jedes [Vektorfeldes](../Vektorfeld.md) $\boldsymbol{v}: D\subseteq{\mathbb{R}^n\to\mathbb{R}^n}$ längs $\gamma$ gilt
>$$\int_\gamma \boldsymbol{v}\cdot\mathop{\mathrm{d}s} = \int_{\gamma_{|[a;c]}} \boldsymbol{v} \cdot \mathop{\mathrm{d}s} + \int_{\gamma_{|[c;b]}} \boldsymbol{v} \cdot \mathop{\mathrm{d}s}$$
>
>>[!PROOF]- Beweis
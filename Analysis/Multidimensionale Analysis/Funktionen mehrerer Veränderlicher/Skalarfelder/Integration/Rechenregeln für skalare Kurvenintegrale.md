>[!THEOREM] Satz: Linearität des skalaren Kurvenintegrals
>Sei $\gamma: [a;b]\to\mathbb{R}^n$ eine [Kurve](../../Kurven/Kurve.md).
>
>Für alle $\lambda,\mu\in\mathbb{R}$ und alle [Skalarfelder](../Skalarfeld.md) $f,g:D\subseteq\mathbb{R}^n\to\mathbb{R}$ gilt für das [skalare Kurvenintegral](Skalares%20Kurvenintegral.md)
>$$\int_\gamma (\lambda\, f +\mu \, g)\mathop{\mathrm{d}s} = \lambda\int_\gamma f\mathop{\mathrm{d}s} + \mu \int_\gamma g\mathop{\mathrm{d}s} $$
>>[!PROOF]- Beweis
>>Laut Definition
>>$$\begin{align}\int_\gamma (\lambda\, f +\mu \, g)\mathop{\mathrm{d}s} &=\int_a^b [\lambda\, f(\gamma(t)) +\mu \, g(\gamma(t))]\,||\dot{\gamma}(t)||\mathop{\mathrm{d}t} \\ &=\int_a^b \lambda\, f(\gamma(t))\,||\dot{\gamma}(t)|| +\mu \, g(\gamma(t))\,||\dot{\gamma}(t)||\mathop{\mathrm{d}t} \\ &= \lambda \int_a^b f(\gamma(t)) \, ||\dot{\gamma}(t)|| \mathop{\mathrm{d}t} + \mu \int_a^b g(\gamma(t))\,||\dot{\gamma}(t)||\mathop{\mathrm{d}t} \\ &= \lambda\int_\gamma f\mathop{\mathrm{d}s} + \mu \int_\gamma g\mathop{\mathrm{d}s} \end{align}$$

>[!THEOREM] Satz: Zerlegungsadditivität des skalaren Kurvenintegrals
>Seien $\gamma_{|[a;c]}:[a;c]\to\mathbb{R}^n$ und $\gamma_{|[c;b]}:[c;b]\to\mathbb{R}^n$ zwei [Kurven](../../Kurven/Kurve.md) mit $\gamma_{|[a;c]}(c) = \gamma_{|[c;b]}(c)$ und sei $\gamma:[a;b]$ die aus $\gamma_{|[a;c]}$ und $\gamma_{|[c;b]}$ zusammengesetzte [[Kurve]].
> $$\gamma(t) = \begin{cases}\gamma_{|[a;c]}(t) \qquad t \in [a;c] \\ \gamma_{|[c;b]}(t) \qquad t\in [c;b]\end{cases}$$
>
>Für das [skalare Kurvenintegral](Skalares%20Kurvenintegral.md) jedes [Skalarfeldes](../Skalarfeld.md) $f: D\subseteq{\mathbb{R}^n\to\mathbb{R}}$ längs $\gamma$ gilt
>$$\int_\gamma f\mathop{\mathrm{d}s} = \int_{\gamma_{|[a;c]}} f\mathop{\mathrm{d}s} + \int_{\gamma_{|[c;b]}} f\mathop{\mathrm{d}s}$$
>
>>[!PROOF]- Beweis
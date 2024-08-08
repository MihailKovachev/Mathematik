>[!THEOREM] Satz: Fundamentalsatz für vektorielle Kurvenintegrale
>Ist $\boldsymbol{v}:D\subseteq\mathbb{R}^n\to\mathbb{R}^n$ ein [stetiges](../Stetigkeit%20von%20Vektorfeldern.md) [Gradientenfeld](Gradientenfeld%20und%20Stammfunktion.md) mit einer [Stammfunktion](Gradientenfeld%20und%20Stammfunktion.md) $f$, so gilt für das [vektorielle Kurvenintegral](../Integration/Vektorielles%20Kurvenintegral.md) längs jeder [stückweisen stetig differenzierbaren](../../Kurven/Differentiation/Differenzierbarkeit%20von%20Kurven.md) [Kurve](../../Kurven/Kurve.md) $\gamma: [a;b]\to D$
>$$\int_\gamma \boldsymbol{v}\cdot\mathop{\mathrm{d}\vec{s}} = f(\gamma(b))-f(\gamma (a))$$
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Vektorielle Kurvenintegrale längs geschlossener Kurven
>Ist $\boldsymbol{v}: D\subseteq\mathbb{R}^n\to \mathbb{R}^n$ ein [Gradientenfeld](../../Skalarfelder/Differentiation/Gradient.md), so ist das [vektorielle Kurvenintegral](../Integration/Vektorielles%20Kurvenintegral.md) längs jeder [geschlossenen Kurve](../../Kurven/Geschlossene%20Kurve.md) $\mathcal{C}$ null.
>$$\oint_\mathcal{C}\boldsymbol{v}\cdot\mathop{\mathrm{d}\vec{s}} = 0$$
>>[!PROOF]- Beweis

>[!THEOREM] Satz: Wegunabhängigkeit des vektoriellen Kurvenintegrals
>Sei $\boldsymbol{v}$ ein [Gradientenfeld](Gradientenfeld%20und%20Stammfunktion.md).
>
>Sind $\mathcal{C}_1$ und $\mathcal{C}_2$ zwei [Kurven](../../Kurven/Kurve.md) mit [Parametrisierungen](../../Kurven/Kurve.md) jeweils $\mathbf{u}$ und $\mathbf{v}$, die dieselben Anfangs- und Endpunkte haben, so sind die [vektoriellen Kurvenintegrale](../Integration/Vektorielles%20Kurvenintegral.md) von $\boldsymbol{v}$ längs $\mathcal{C}_1$ und $\mathcal{C}_2$ gleich.
>$$\int_{\mathcal{C}_1} \boldsymbol{v}\cdot \mathop{\mathrm{d}\vec{s}} = \int_{\mathcal{C}_2} \boldsymbol{v}\cdot \mathop{\mathrm{d}\vec{s}}$$
>>[!PROOF]- Beweis
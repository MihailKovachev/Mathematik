>[!DEFINITION] Definition: Skalares Kurvenintegral
>Seien $f:D\subseteq \mathbb{R}^n\to\mathbb{R}$ ein [Skalarfeld](../Skalarfeld.md) und $\mathcal{C}\subseteq D$ eine [Kurve](../../Kurven/Kurve.md). 
>
>Für jede [Kurvenparametrisierung](../../Kurven/Kurve.md) $\gamma: [a;b] \to \mathbb{R}^n$ von $\mathcal{C}$ definiert man das **skalare Kurvenintegral** von $f$ längs $\mathcal{C}$ durch das [bestimmte Integral](../../../../Eindimensionale%20Analysis/Integration/Bestimmte%20Integrale/Bestimmtes%20(Riemann-)Integral.md)
>
>$$\int_a^b f(\gamma(t))\,||\dot{\gamma}(t)||\mathop{\mathrm{d}t}$$
>
>>[!THEOREM] Satz: Eindeutigkeit des skalaren Kurvenintegrals
>>Für je zwei [Kurvenparametrisierungen](../../Kurven/Kurve.md) $\gamma: [a;b] \to \mathbb{R}^n$ und $\varphi: [c;d] \to \mathbb{R}^n$ von $\mathcal{C}$ gilt
>>
>>$$\int_a^b f(\gamma(t))||\dot\gamma (t)||\mathop{\mathrm{d}t} = \int_c^d f(\varphi(t))||\dot\varphi (t)||\mathop{\mathrm{d}t}$$
>>>[!PROOF]- Beweis
>
>>[!NOTATION] Bezeichnung
>>Da das skalare Kurvenintegral unabhängig von der Kurvenparametrisierung ist, bezeichnet man es im Allgemeinen als
>>$$\int_\mathcal{C} f \mathop{\mathrm{d}s}$$
>>
>>Falls $\mathcal{C}$ [geschlossen](../../Kurven/Geschlossene%20Kurve.md) ist, schreibt man
>>$$\oint_\mathcal{C} f \mathop{\mathrm{d}s}$$
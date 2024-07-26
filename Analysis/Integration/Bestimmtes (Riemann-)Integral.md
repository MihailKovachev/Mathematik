> [!DANGER] Definition: Bestimmtes (Riemann-)Integral
> Eine [Funktion](../Funktionen/Funktion.md) $f: [a;b] \to \mathbb{R}$ heißt **(Riemann-)integrierbar** auf $[a;b]$, falls alle ihre [Riemann-Summen](Riemann-Summen.md) gegen eine bestimmte Zahl $S$ für $\Delta x_i \to 0$ konvergieren. 
> $$\lim_{\Delta x_i\to 0}\sum_{i=1}^n f(x_i^\ast)\Delta x_i = S \in \mathbb{R}$$
> 
> Die Zahl $S$ nennt man das **bestimmte (Riemann-)Integral** von $f$.
> $$\int_a^b f(x)\mathop{\mathrm{d}x} \overset{\text{def}}{=} \lim_{\Delta x_i\to 0}\sum_{i=1}^n f(x_i^\ast)\Delta x_i = S$$
> > [!QUOTE] Geometrische Bedeutung des bestimmten Integrals
> > Das bestimmte Integral $\int_a^b f(x) \mathop{\mathrm{d}x}$ ergibt den signierten Flächeninhalt zwischen dem Graphen von $f$ und die Linie zwischen den Punkten $a$ und $b$ auf der $x$-Achse.
> > 
> > Es ergibt den *signierten* Flächeninhalt, weil man Flächen unter der $x$-Achse als negativ betrachtet. 
> > ![](Resources/Bestimmtes%20Integral.png)
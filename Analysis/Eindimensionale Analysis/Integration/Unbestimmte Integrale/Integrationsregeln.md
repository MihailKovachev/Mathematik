> [!THEOREM] Satz: Linearität der [Integration](Stammfunktion.md)
> Für alle $\lambda, \mu \in \mathbb{R}$  gilt
> $$\int \lambda \, f(x) + \mu \, g(x) \mathop{\mathrm{d}x} = \lambda \int f(x) \mathop{\mathrm{d}x} + \mu \int g(x) \mathop{\mathrm{d}x}$$
> > [!PROOF]- Beweis
> > Sei $F(x)$ eine [Stammfunktion](Stammfunktion.md) von $f(x)$ und $G(x)$ - eine Stammfunktion von $g(x)$.
> > 
> > Wir betrachten die [Ableitung](../../Differentiation/Ableitung%20und%20Differenzierbarkeit.md) der rechten Seite.
> > $$\frac{\mathrm{d}}{\mathrm{d}x}\left(\lambda \int f(x) \mathop{\mathrm{d}x} + \mu \int g(x) \mathop{\mathrm{d}x}\right)$$
> > Laut der Linearität der Ableitung gilt
> > $$\begin{align}\frac{\mathrm{d}}{\mathrm{d}x}\left(\lambda \int f(x) \mathop{\mathrm{d}x} + \mu \int g(x) \mathop{\mathrm{d}x}\right) &= \lambda\frac{\mathrm{d}}{\mathrm{d}x}\int f(x) \mathop{\mathrm{d}x} + \mu \frac{\mathrm{d}}{\mathrm{d}x}\int g(x) \mathop{\mathrm{d}x} \\ &= \lambda\frac{\mathrm{d}}{\mathrm{d}x} F(x) + \mu\frac{\mathrm{d}}{\mathrm{d}x}G(x) \\ &= \lambda f(x) + \mu g(x)\end{align}$$
> > 
> > Das heißt, $\lambda F(x) + \mu G(x)$ ist für jede Stammfunktionen $F(x)$ und $G(x)$ von jeweils $f(x)$ und $g(x)$ eine Stammfunktion von $\lambda \, f(x) + \mu \, g(x)$. Den Rest der Stammfunktionen von $\lambda \, f(x) + \mu \, g(x)$ kann man dann als $\lambda F(x) + \mu G(x) + C$ für ein entsprechendes $C\in \mathbb{R}$ darstellen.

> [!THEOREM] Satz: Partielle [Integration](Stammfunktion.md)
> $$\int u(x) v'(x) \mathop{\mathrm{d}x} = u(x)v(x) + \int u'(x)v(x) \mathop{\mathrm{d}x}$$
> > [!PROOF]- Beweis

> [!THEOREM] Satz: Substitutionsregel
> $$\int f(\underset{u}{\underbrace{g(x)}})\underset{\mathop{\mathrm{d}u}}{\underbrace{g'(x) \mathop{\mathrm{d}x}}} = \int f(u) \mathop{\mathrm{d}u}$$
> > [!PROOF]- Beweis

> [!THEOREM] Satz: Ableitungsdivision
> $$\int \frac{f'(x)}{f(x)} \mathop{\mathrm{d}x} = \ln (f(x)) + C, \qquad f(x) \gt  0$$
> > [!PROOF]- Beweis
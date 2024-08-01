> [!THEOREM] Satz: Differenzierbarkeit $\implies$ Stetigkeit
> Ist $f: D\subseteq \mathbb{R}\to\mathbb{R}$ in $x_0\in D$ [differenzierbar](Ableitung%20und%20Differenzierbarkeit.md), so ist $f$ auch [stetig](../Grenzwerte%20von%20Funktionen/Stetigkeit/Stetigkeit.md) in $x_0$.
> > [!PROOF]- Beweis
> > Sei $f: D\subseteq \mathbb{R}\to\mathbb{R}$ in $x_0$ differenzierbar. Dann existiert
> > $$\lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x)-f(x_0)}{\Delta x} = f'(x_0) \in \mathbb{R}$$
> > Dies kann folgendermaßen umgewandelt werden, indem wir $x = x_0 + \Delta x$ setzen:
> > $$\lim_{x\to x_0}\frac{f(x)-f(x_0)}{x-x_0} = f'(x_0)$$
> > Wir müssen zeigen, dass $\displaystyle \lim_{x\to x_0} f(x) = f(x_0)$ bzw. $\displaystyle \lim_{x\to x_0} f(x) - f(x_0) = 0$.
> > 
> > $$\begin{align}\lim_{x\to x_0} f(x) - f(x_0) &= \lim_{x\to x_0} (f(x)-f(x_0))\frac{x-x_0}{x-x_0} \\ &= \left(\lim_{x\to x_0}\frac{f(x) - f(x_0)}{x-x_0}\right) (x-x_0) \\ &= \left(\lim_{x\to x_0}\frac{f(x) - f(x_0)}{x-x_0}\right) \left(\lim_{x\to x_0} x - x_0\right)  \\ &= f'(x_0) \cdot 0 = 0\end{align}$$
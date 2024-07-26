---
Related:
- "[[Ableitung und Differenzierbarkeit]]"
---

> [!IMPORTANT] Satz: Linearität
> Sind $f$ und $g$ in $x$ differenzierbar, dann gilt für alle $\lambda,\mu\in\mathbb{R}$
> $$[\lambda\, f(x) + \mu\, g(x)]' = \lambda\, f'(x) + \mu\, g'(x)$$
> > [!CHECK]- Beweis
> > $$\begin{align}[\lambda\, f(x) + \mu\, g(x)]' &= \operatorname*{lim}_{\Delta x\rightarrow0}\frac{\lambda f(x_{0}+\Delta x)+\mu g(x_{0}+\Delta x) - \lambda f(x_{0})-\mu g(x_{0})}{\Delta x}\\ &= \lim_{\Delta x\to 0}\frac{\lambda[f(x_{0}+\Delta x)-f(x_{0})] + \mu[g(x_{0}+\Delta x)-g(x_{0})]}{\Delta x} \\ &= \lim_{\Delta x\to 0}\lambda\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x} + \lim_{\Delta x\to 0}\mu\frac{g(x_0+\Delta x)-g(x_0)}{\Delta x} \\ &= \lambda\lim_{\Delta x\to 0}\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x} + \mu\lim_{\Delta x\to 0}\frac{g(x_0+\Delta x)-g(x_0)}{\Delta x} \\ &= \lambda f'(x_0) + \mu g'(x_0)\end{align}$$

> [!IMPORTANT] Satz: Produktregel
> Sind $f$ und $g$ in $x$ differenzierbar, dann gilt
> $$[f(x)g(x)]' = f'(x)g(x) + f(x)g'(x)$$

> [!IMPORTANT] Satz: Quotientenregel
> Sind $f$ und $g$ in $x$ differenzierbar mit $g(x)\ne 0$, dann gilt
> $$\left[\frac{f(x)}{g(x)}\right]' = \frac{f'(x)g(x)-f(x)g'(x)}{g(x)^2}$$

> [!IMPORTANT] Satz: Allgemeine Potenzregel
> Sind $f$ und $g$ in $x$ differenzierbar, so gilt
> $$\left[f(x)^{g(x)}\right]' = f(x)^{g(x)}\left[f'(x)\frac{g(x)}{f(x)} + g'(x)\ln(f(x))\right]$$

> [!IMPORTANT] Satz: Kettenregel
> Sind $g$ in $x$ und $f$ in $g(x)$ differenzierbar, dann gilt
> $$[f(g(x))]' = f'(g(x))g'(x)$$

> [!IMPORTANT] Satz: Ableitung der Umkehrfunktion
> Ist $f$ umkehrbar und differenzierbar in $x = f^{-1}(y)$ mit $f(x) \ne 0,$ dann gilt
> $$[f^{-1}(y)]' = \frac{1}{f'(f^{-1}(y))}$$
> > [!CHECK]- Beweis
> > Da $f^{-1}$ die Umkehrfunktion von $f$ ist, gilt
> > $$f^{-1}(f(x)) = x$$
> > Nach Ableitung auf den beiden Seiten ergibt sich
> > $$\frac{d}{dx}[f^{-1}(f(x))] = \frac{d}{dx}x$$
> > $$[f^{-1}(f(x))]' \cdot f'(x) = 1$$
> > $$[f^{-1}(y)]'\cdot f'(f^{-1}(y)) = 1$$
> > $$[f^{-1}(y)]' = \frac{1}{f'(f^{-1}(y))}$$
---
Related:
- "[[Potenzreihe]]"
- "[[Konvergenzbereich]]"
---

> [!IMPORTANT] Satz: Existenz des Konvergenzradius
> Zu jeder [Potenzreihe](Potenzreihe.md) $f(x)=\displaystyle \sum_{k=0}^{\infty}a_{k}(x-x_{0})^{k}$ gibt es ein $r \in \mathbb{R}_{\ge 0} \cup \{\infty\}$, für das gilt:
> - $f(x)$ konvergiert absolut $\forall x$ mit $|x-x_0|\lt r$
> - $f(x)$ divergiert $\forall x$ mit $|x-x_0|\gt r$
> - $f(x)$ konvergiert für $x=x_0$, falls $r=0$
> - $f(x)$ konvergiert $\forall x\in\mathbb{R}$, falls $r=\infty$
> 
> > [!DANGER] Definition: Konvergenzradius
> > Die Zahl $r$ nennt man den *Konvergenzradius* der Potenzreihe $f(x)$.
> 
> > [!NOTE] Notiz: $|x-x_0|=r$
> > Im Falle von $|x-x_0|=r$ ist keine allgemeine Aussage möglich.

> [!IMPORTANT] Satz: Berechnung des Konvergenzradius
> Für den Konvergenzradius $r$ einer Potenzreihe $f(x)=\displaystyle \sum_{k=0}^{\infty}a_{k}(x-x_{0})^{k}$ gelten
> $$r = \lim_{k\to\infty} \left|\frac{a_{k+1}}{a_k}\right|$$
> $$r = \operatorname*{lim}_{k\rightarrow\infty}\frac{1}{\sqrt[k]{|a_{k}|}}$$
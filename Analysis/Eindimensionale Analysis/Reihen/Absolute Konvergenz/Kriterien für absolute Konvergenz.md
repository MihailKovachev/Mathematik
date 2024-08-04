> [!THEOREM] Satz: Quotientenkriterium
> Die [Reihe](../Reihe.md) $\displaystyle \sum_{k=1}^\infty a_k$ ist:
> - [absolut konvergent](Absolute%20Konvergenz.md), falls
> $$\exists\lim_{k\to\infty} \left|\frac{a_{k+1}}{a_k}\right| \lt 1$$
> 
> - [divergent](../../Folgen/Grenzwerte/Konvergenz/Konvergenz.md), falls
> 
> $$\exists\lim_{k\to\infty} \left|\frac{a_{k+1}}{a_k}\right| \gt 1$$
> 
> > [!NOTE]
> > Wenn $\displaystyle \lim_{k\to\infty} \left|\frac{a_{k+1}}{a_k}\right| = 1$,  lässt sich durch dieses Kriterium nicht bestimmen, ob die Reihe (absolut) konvergiert oder divergiert.

> [!THEOREM] Satz: Wurzelkriterium
> Die Reihe $\displaystyle \sum_{k=1}^\infty a_k$ ist:
> - absolut konvergent, falls
> 
> $$\exists\lim_{k\to\infty} \sqrt[k]{|a_k|} \lt 1$$
> 
> - divergent, falls
> 
> $$\exists\lim_{k\to\infty} \sqrt[k]{|a_k|} \gt 1$$
> 
> > [!NOTE]
> > Wenn $\displaystyle \lim_{k\to\infty} \sqrt[k]{a_k} = 1$,  lässt sich durch dieses Kriterium nicht bestimmen, ob die Reihe (absolut) konvergiert oder divergiert.

> [!THEOREM] Satz: Majorantentkriterium
> Die Reihe $\displaystyle \sum_{k=1}^\infty a_k$ konvergiert absolut, wenn es eine konvergente Reihe $\displaystyle \sum_{k=1}^\infty b_k$ gibt, sodass
> $$|a_k| \le b_k \,\, \forall k\ge N \in\mathbb{N}$$
> 
> > [!NOTE] Majorante
> > Die Reihe $\displaystyle \sum_{k=1}^\infty b_k$ nennt man eine **Majorante** von $\displaystyle \sum_{k=1}^\infty a_k$.
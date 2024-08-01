> [!THEOREM] Satz: Konvergenzkriterium
> Eine [Folge](../../Folge.md) $(a_n)_{n\in\mathbb{N}}$ ist genau dann gegen $L$ konvergent, wenn 
> $$\lim_{n\to\infty} |a_n - L| = 0$$
> > [!PROOF]- Beweis
> > Wir müssen beide Richtungen beweisen.
> > 
> > Zunächst sei $(a_n)_{n\in\mathbb{N}}$ konvergent gegen $L$, also gibt es für jedes $\varepsilon \gt 0$ ein $n \in \mathbb{N}$ derart, dass
> > $$|a_n - L| \lt \varepsilon, \forall n \ge N$$
> > Betrachten wir die Folge $(|a_n - L|)_{n\in\mathbb{N}}$. Es gilt
> > $$|a_n - L| \le |a_n| + |L|$$
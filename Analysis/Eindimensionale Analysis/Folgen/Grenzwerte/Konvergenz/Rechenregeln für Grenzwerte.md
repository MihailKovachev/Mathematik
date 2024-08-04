> [!THEOREM] Satz: Rechenregeln für Grenzwerte
> Seien $(a_n)_{n\in\mathbb{N}}$ und $(b_n)_{n\in\mathbb{N}}$ zwei [konvergente](Konvergenz.md) [Folgen](../../Folge.md) mit $\displaystyle \lim_{n\to\infty} a_n = a$ und $\displaystyle \lim_{n\to\infty} b_n = b$. Dann gelten:
> $$\lim_{n\to\infty} (a_n \pm b_n) = \lim_{n\to\infty} a_n \pm \lim_{n\to\infty} b_n = a \pm b$$
> $$\lim_{n\to\infty} (a_n \cdot b_n) = \left(\lim_{n\to\infty} a_n\right)\cdot\left(\lim_{n\to\infty} b_n\right) = a\cdot b$$
> $$\lim_{n\to\infty} \frac{a_n}{b_n} = \frac{\displaystyle\lim_{n\to\infty} a_n}{\displaystyle\lim_{n\to\infty} b_n} = \frac{a}{b}, b \ne 0$$
> $$\lim_{n\to\infty} (\lambda \cdot a_n) = \lambda \cdot \lim_{n\to\infty} a_n = \lambda \cdot a, \forall\lambda \in \mathbb{R}$$
> > [!PROOF]- Beweis
> > 1. Zunächst befassen wir uns mit
> >
> > 	$$\lim_{n\to\infty} (a_n + b_n) = \lim_{n\to\infty} a_n + \lim_{n\to\infty} b_n = a + b$$
> > 
> > 	Sei $\varepsilon \gt 0$. Definitionsgemäß gibt es $N_a,N_b\in\mathbb{N}$ mit
> > 
> > 	$$|a_n - a| \lt \frac{\varepsilon}{2}, \forall n \ge N_a$$
> > 	$$|b_n - b| \lt \frac{\varepsilon}{2},\forall n \ge N_b$$
> > 	
> > 	Für alle $n\ge \max \{N_a, N_b\}$ ergibt sich daraus
> > 	$$|a_n + b_n - (a+b)| = |a_n - a + b_n - b| \le |a_n - a| + |b_n - b| \lt \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon$$
> 
> > [!WARNING] Warnung
> > Diese Regeln gelten nur für *konvergente* Folgen.
---
Related:
  - "[[../../Folge|Folge]]"
  - "[[Konvergenz|Konvergenz]]"
  - "[[../../Beschränktheit/Beschränktheit reeller Folgen|Beschränktheit reeller Folgen]]"
---

> [!IMPORTANT] Satz: Beschränktheit konvergenter reeller Folgen
> Jede konvergente reelle Folge ist beschränkt.
> > [!CHECK]- Beweis
> > Sei $(a_n)_{n\in\mathbb{N}}$ eine konvergente Folge, die gegen $L$ konvergier. Das heißt, für jedes $\varepsilon \gt 0$ gibt es ein $N \in \mathbb{N}$ mit
> > $$|a_n - L| \lt \varepsilon, \forall n \ge N$$
> > Wir wählen $\varepsilon = 1$. Dann ergibt sich
> > $$|a_n| = |a_n - L + L| \le |a_n - L|+|L| \lt 1 + |L|, \forall n \ge N$$
> > Die Folge ist dann für jedes $n \ge N$ kleiner als $1 + |L|$ und auch größer als $-(1+|L|)$ und ist somit nach oben und nach unten beschränkt. Also ist die Folge von $N$ an beschränkt. Die Menge $\{a_1,\cdots,a_N\}$ der Elemente der Folge vor $N$ ist endlich und jede endliche Folge ist von ihrem Minimum- und Maximumelementen beschränkt. Das heißt, die ganze Folge $(a_n)_{n\in\mathbb{N}}$ ist beschränkt.
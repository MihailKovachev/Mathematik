> [!THEOREM] Lemma: Quetschlemma (Sandwichlemma)
> Seien $(a_n)_{n\in\mathbb{N}}$ und $(b_n)_{n\in\mathbb{N}}$ zwei gegen $L$ [konvergente](Konvergenz.md) [Folgen](../../Folge.md). Für jede Folge $(c_n)_{n\in\mathbb{N}}$ mit $a_n \le c_n \le b_n$ für alle $n$ nach einem $n_0\in\mathbb{N}$ gilt
> $$\lim_{n\to\infty} c_n = \lim_{n\to\infty} a_n = \lim_{n\to\infty} b_n = L$$
> > [!PROOF]- Beweis
> > Sei $\varepsilon \gt 0$. Da $(a_n)_{n\in\mathbb{N}}$ und $(b_n)_{n\in\mathbb{N}}$ gegen $L$ konvergieren, existieren $N_1,N_2$ mit
> > $$|a_n - L| \lt \varepsilon, \forall n \ge N_1 \text{ und } |b_n - L| \lt \varepsilon, \forall n \ge N_2$$
> > Des Weiteren existiert nach Voraussetzung ein $n_0 \in \mathbb{N}$ mit
> > $$a_n \le c_n \le b_n, \forall n \ge n_0$$
> > Folglich ergibt sich
> > $$L - \varepsilon \lt a_n \le c_n \le b_n \lt L + \varepsilon, \forall n \ge \max \{n_0, N_1, N_2\}$$
> > Also
> > $$|c_n - L| \lt \varepsilon, \forall n \ge \max \{n_0, N_1, N_2\}$$
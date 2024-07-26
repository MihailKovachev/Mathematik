> [!IMPORTANT] Satz: Nichtkommutativität
> Für zwei Matrizen $A \in K^{m \times n}$ und $B\in K^{n \times p}$ ist im Allgemeinen
> $$A\cdot B \ne B \cdot A$$
> > [!NOTE] Notiz
> > Es kann sein, dass $A\cdot B = B \cdot A$, aber nur, wenn $A$ und $B$ [quadratische](../Matrix.md) Matrizen sind und doch auch nicht immer!

> [!IMPORTANT] Satz: Assoziativität
> Für alle [Matrizen](../Matrix.md) $A \in K^{m\times n}, B \in K^{n\times p}$ und $C \in K^{p\times q}$ gilt
> $$A\cdot(B\cdot C) = (A\cdot B)\cdot C$$

> [!IMPORTANT] Satz: Distributivität
> Distributivität I:
> - Für alle $A, B \in K^{m\times n}$ und $C \in K^{n\times p}$ gilt
> $$(A + B)\cdot C = A\cdot C + B \cdot C$$
> 
> Distributivität II:
> - Für alle $A \in K^{m\times n}$ und $B, C \in K^{n \times p}$gilt
> $$A\cdot (B + C) = A\cdot B + A \cdot C$$

> [!IMPORTANT] Satz: Multiplikation mit der Einheitsmatrix
> Für jede [quadratische](../Matrix.md) Matrix $A \in K^{n\times n}$ und die [Identitätsmatrix](../Matrix.md) $I_n$ gilt
> $$A \cdot I_n = I_n \cdot A = A$$
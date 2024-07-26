> [!IMPORTANT] Satz: Distributivität
> Für die [Determinante](Determinante.md) des [Produkts](../Matrizenoperationen/Multiplikation%20von%20Matrizen.md) zweier [Matrizen](../Matrix.md) $A, B \in K^{n\times n}$ gilt
> $$\det (AB) = \det(A)\det(B) = \det(B)\det(A) = \det (BA)$$

> [!IMPORTANT] Satz: Determinante des Transponierten
> Für die [Determinante](Determinante.md) des [Transponierte](../Matrizenoperationen/Transponieren.md) einer [Matrix](../Matrix.md) $A \in K^{n\times n}$ gilt
> $$\det(A^\mathsf{T}) = \det(A)$$

> [!IMPORTANT] Satz: Determinante des Inversen
> Falls die [Matrix](../Matrix.md) $A\in K^{n\times n}$ [invertierbar](../Invertieren/Invertierbarkeit.md) ist, gilt
> $$\det(A^{-1}) = \frac{1}{\det(A)}$$

> [!IMPORTANT] Satz: Determinante des skalaren Fachen
> Für jede [Matrix](../Matrix.md) $A\in K^{n\times n}$ gilt
> $$\det(\alpha A) = \alpha^n \det (A) \qquad \alpha \in K$$
> > [!CHECK]- Beweis
> > Das Multiplizieren von $A$ mit $\alpha$ ist dazu äquivalent, jede Zeile von $A$ mit $\alpha$ zu multiplzieren. Aber [Multiplikation einer Zeile oder Spalte](Effekt%20von%20Zeilen-%20und%20Spaltenumformungen.md) von $A$ mit $\alpha \in K$ bewirkt eine Multiplikation der Determinante mit $\alpha$. Die Matrix hat $n$ Zeilen und das ergibt $\alpha^n$.
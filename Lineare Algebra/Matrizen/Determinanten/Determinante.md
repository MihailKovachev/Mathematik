> [!DANGER] Definition: Determinante
> Die **Determinante** $\det: K^{n\times n}\to K$ ist eine rekursiv definierte [Abbildung](../../../Mengenlehre/Abbildungen/Abbildung.md), die jeder [quadratischen Matrix](../Matrix.md) $A\in K^{n\times n}$ eine Zahl $\det (A)$ zuordnet:
> $$\det(A) = \begin{cases}a_{11}, \text{ falls } n = 1 \\ \displaystyle\sum_{i=1}^n (-1)^{1+j}a_{1j}\det(A_{1j}), \text{ falls } n\gt 1\end{cases}$$
> > [!NOTE] Schreibweise
> > Oftmals schreibt man $|A|$ anstelle von $\det (A)$.
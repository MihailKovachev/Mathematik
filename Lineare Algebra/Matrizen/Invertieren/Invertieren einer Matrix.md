> [!ALGORITHM] Algorithmus: Invertieren einer Matrix
> Sei $A\in K^{n\times n}$ eine [invertierbare](Invertierbarkeit.md) [Matrix](../Matrix.md). Um das Inverse $A^{-1}$ zu finden:
> 1. Notiere die [erweiterte Koeffizientenmatrix](../../Lineare%20Gleichungssysteme/Koeffizientenmatrix.md) $[A\mid I_n]$, wo $I_n$ die $n\times n$-[Identitätsmatrix](../Matrix.md) ist.
> 2. Führe [das Gauß-sche Eliminationsverfahren](../../Lineare%20Gleichungssysteme/Lösen%20von%20LGS/Das%20Gauß-sche%20Eliminationsverfahren.md) durch, bis auf der linken Seite der erweiterten Koeffizientenmatrix $[A\mid I_n]$ die Identitätsmatrix $I_n$ erscheint.
> 3. Auf der rechten Seite steht nun das Inverse $A^{-1}$.
> $$[A\mid I_n] \approx \cdots \approx [I_n\mid A^{-1}]$$
> 
> > [!EXAMPLE]- Beispiel
> > Wir betrachten die Matrix $A = \begin{bmatrix}6 & 8 & 3 \\ 4 & 7 & 3 \\ 1 & 2 & 1\end{bmatrix}$. Dazu notieren wir
> > $$[A\mid I_3] = \left[\begin{array}{ccc|ccc}6 & 8 & 3 & 1 & 0 & 0\\ 4 & 7 & 3 & 0 & 1 & 0 \\ 1 & 2 & 1 & 0 & 0 & 1\end{array}\right]$$
> > Jetzt versuchen wir die linke Seite auf [reduzierte Zeilenstufenform](../Zeilenstufenform/Zeilenstufenform.md) zu bringen.
> > $$\left[\begin{array}{ccc|ccc}6 & 8 & 3 & 1 & 0 & 0\\ 4 & 7 & 3 & 0 & 1 & 0 \\ 1 & 2 & 1 & 0 & 0 & 1\end{array}\right] \approx \left[\begin{array}{ccc|ccc}1 & 2 & 1 & 0 & 0 & 1 \\ 6 & 8 & 3 & 1 & 0 & 0\\ 4 & 7 & 3 & 0 & 1 & 0 \end{array}\right] \approx \left[\begin{array}{ccc|ccc}1 & 2 & 1 & 0 & 0 & 1 \\ 0 & -4 & -3 & 1 & 0 & -6\\ 0 & -1 & -1 & 0 & 1 & -4 \end{array}\right]$$
> > $$\left[\begin{array}{ccc|ccc}1 & 2 & 1 & 0 & 0 & 1 \\ 0 & -4 & -3 & 1 & 0 & -6\\ 0 & -1 & -1 & 0 & 1 & -4 \end{array}\right] \approx \left[\begin{array}{ccc|ccc}1 & 0 & -1 & 0 & 2 & -7 \\ 0 & 1 & 1 & 0 & -1 & 4\\ 0 & 0 & 1 & 1 & -4 & 10 \end{array}\right] \approx \left[\begin{array}{ccc|ccc}1 & 0 & 0 & 1 & -2 & 3 \\ 0 & 1 & 0 & -1 & 3 & -6\\ 0 & 0 & 1 & 1 & -4 & 10 \end{array}\right]$$
> > Nach dem [Satz der Invertierbarkeit](Satz%20der%20Invertierbarkeit.md) ist $A$ invertierbar, denn auf der linken Seite gibt es keine Nullzeilen. Die rechte Seite ist dann $A^{-1}$.
> > $$A^{-1} = \begin{bmatrix}1 & -2 & 3 \\ -1 & 3 & -6 \\ 1 & -4 & 10\end{bmatrix}$$

> [!THEOREM] Satz: Invertieren einer $2\times 2$-Matrix
> Eine Matrix $A = \begin{bmatrix}a & b \\ c & d\end{bmatrix}$ ist genau dann invertierbar, wenn
> $$ad - bc = 0$$
> 
> Falls $A = \begin{bmatrix}a & b \\ c & d\end{bmatrix}$ invertierbar ist, gilt
> $$A^{-1} = \frac{1}{ad-bc}\begin{bmatrix}d & -b \\ -c & a\end{bmatrix}$$
> > [!PROOF]- Beweis
> > TODO

> [!THEOREM] Satz: Invertieren von Diagonalmatrizen
> Für jede Diagonalmatrix $D = \operatorname{diag}(\lambda_1, \cdots,\lambda_n)$ gilt $D^{-1} = \operatorname{diag}(\lambda_1^{-1}, \cdots,\lambda_n^{-1})$.
> $$\begin{bmatrix}\lambda_1 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & \lambda_n\end{bmatrix}^{-1} = \begin{bmatrix}\displaystyle\frac{1}{\lambda_1} & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & \displaystyle\frac{1}{\lambda_n}\end{bmatrix}$$
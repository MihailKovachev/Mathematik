> [!THEOREM] Satz: Die Cramersche Regel
> Ist 
> $$\begin{bmatrix}\vert & \vert & \vert \\ \vec{a}_1 & \cdots & \vec{a}_n \\ \vert & \vert & \vert\end{bmatrix}\begin{bmatrix}x_1 \\ \vdots \\ x_n\end{bmatrix} = \vec{b}$$
> ein [lösbares](Lösbarkeit.md) [lineares Gleichungssystem](Lineares%20Gleichungssystem.md), so lässt sich die Lösung des $i$-ten Unbekannten $x_i$ folgenermaßen durch die [Determinante](../../Matrizen/Quadratische%20Matrizen/Determinanten/Determinante.md) der [Koeffizientenmatrix](Koeffizientenmatrix.md)  bestimmen:
> $$x_i = \frac{\det\begin{bmatrix}\vert & \vert & \vert & \vert & \vert & \vert & \vert\\ \vec{a}_1 & \cdots & \vec{a}_{i-1} & \vec{b} & \vec{a}_{i+1}& \cdots & \vec{a}_n \\ \vert & \vert & \vert & \vert & \vert & \vert & \vert\end{bmatrix}}{\det\begin{bmatrix}\vert & \vert & \vert \\ \vec{a}_1 & \cdots & \vec{a}_n \\ \vert & \vert & \vert\end{bmatrix}}$$
> 
> Wir ersetzen die $i$-te Spalte der Koeffizientenmatrix durch $\vec{b}$ und dividieren die Determinante der Ergebnismatrix durch die Determinante der Koeffizientenmatrix.
> > [!PROOF]- Beweis
> > 